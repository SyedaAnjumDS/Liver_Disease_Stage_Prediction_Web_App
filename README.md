**Project Title:** **🩺 Liver Disease Stage Prediction Web App**                                                                                                                                                  
->A fully interactive, end-to-end machine learning web application built with Streamlit that predicts the stage of liver disease based on patient clinical data.                                                  
->This app supports rich visualizations, multi-model comparison, and real-time prediction using both uploaded data and manual input.

---

**📖 Project Overview:**                                                                                                                                                                                          
->This project aims to assist medical professionals and data scientists by providing a lightweight, intelligent tool to classify liver disease into stages using clinical features.                                
->It supports:
              1.Uploading patient datasets                                                                                                                                                                         
              2.Visual EDA to explore patterns                                                                                                                                                                     
              3.Training 17+ classification models                                                                                                                                                                
              4.Evaluating model performance with metrics and charts                                                                                                                                              
              5.Real-time prediction with form-based manual input                                                                                                                                                  

---

**💡 Key Highlights**                                                                                                                                                                                            
->✅ Fully Automated Workflow                                                                                                                                                                                     
Upload → Clean → Analyze → Train → Predict → Compare
Easy-to-use interface via Streamlit                                                                                                                                                                                

->📊 Exploratory Data Analysis (EDA)                                                                                                                                                                              
Distribution plots, boxplots for outlier detection                                                                                                                                                                 
Pie charts and count plots for categorical feature exploration                                                                                                                                                     

->🧠 ML Models Supported                                                                                                                                                                                          
Linear Models: Logistic Regression, Ridge Classifier, Passive Aggressive, SGD                                                                                                                                      
Tree-Based: Decision Tree, Random Forest, Extra Trees, Bagging, AdaBoost, Gradient Boosting, Histogram Gradient Boosting                                                                                          
Advanced Boosters: LightGBM, XGBoost, CatBoost                                                                                                                                                                    
SVM & Neighbors: Support Vector Machine (SVM), KNN                                                                                                                                                                 
Naive Bayes: GaussianNB, BernoulliNB                                                                                                                                                                              

->📈 Model Evaluation                                                                                                                                                                                             
Accuracy scores                                                                                                                                                                                                    
Confusion matrix heatmaps                                                                                                                                                                                        
Classification reports (Precision, Recall, F1-score)                                                                                                                                                               
Feature importance for tree-based models

->✍ Manual Prediction Input                                                                                                                                                                                    
Enter values manually to get instant prediction results from the selected model                                                                                                                                    
Scaled using the same standard scaler as trained data                                                                          

---

**🧰 Technologies Used**                                                                                                                                                                                        
Python:	Programming language                                                                                                                                                                                       
Streamlit:	Web app framework                                                                                                                                                                                    
pandas:	Data manipulation                                                                                                                                                                                          
numpy:	Numerical operations                                                                                                                                                                                       
seaborn, matplotlib:	Data visualization                                                                                                                                                                           
scikit-learn:	Machine learning models & preprocessing                                                                                                                                                              
imbalanced-learn	SMOTE: for class imbalance                                                                                                                                                                       
xgboost:	Gradient boosting                                                                                                                                                                                        
lightgbm:	Fast gradient boosting                                                                                                                                                                                   
catboost:	Boosting with categorical support                                                                                                                                                                        

---

**📁 Expected Dataset Format**                                                                                                                                                                                  
Your dataset should include the following columns:                                                                                                                                                                
Categorical: Sex, Drug, Edema, Ascites, Hepatomegaly, Spiders                                                                                                  
Numerical: Bilirubin, Copper, Cholesterol, etc.                                                                                                                                                                    
Target: Stage (1, 2, 3, or 4)                                                                                                                                                                                      
Missing values are auto-handled. Label encoding is internally applied.                                                                

---

**⚡ Quick Working of My Web App (All Buttons & Actions)**                                                                                                                                                        
1.📂 Upload CSV                                                                                                                                                                                                  
     Upload your liver dataset (in .csv/Excel format).
     The app reads and previews the data instantly.                                                                                                                                                              

2.📊 EDA (Expanders)                                                                                                                                                                                              
      “Show Distribution Plots”                                                                                                                                                                                  
      → Shows histograms + boxplots for all numeric features.                                                                                                                                                      
      “Show Pie Charts for Categorical Features”                                                                                                                                                                  
      → Displays pie charts for Stage, Sex, Drug, Ascites, etc.                                                                                                                                                    

3.🤖 Model Selection (Dropdown)                                                                                                                                                                                  
     Select any one model from 17+ ML classifiers like: SVM, KNN, Logistic Regression, Random Forest, XGBoost, etc.                                                                                                

4.🧠 Train and Evaluate (Button)                                                                                                                                                                                
      Trains the selected model using the preprocessed dataset.                                                                                                                                                  
      After training, the app shows:Classification report                                                                                                                                                          
                                    Confusion matrix heatmap                                                                                                                                                       
                                    Accuracy                                                                                                                                                                       
                                    Feature importance (for tree models only)                                                                                                                                    

5.📥 Manual Prediction (Expander)                                                                                                                                                                                 
      Fill out the form with patient values manually.                                                                                                                                                            
      Click “Predict on Manual Input”:The app uses the trained model to predict the Stage of liver disease for that input.                                                                                        

---

**📷 Sample Screenshots**                                                                                                                                                                                         
<img width="1920" height="1007" alt="Screenshot (53) - Copy" src="https://github.com/user-attachments/assets/f70bbdb4-44e3-4cbf-82fe-c7f8c01ebf8c" />
<img width="1920" height="1011" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/a8b30669-cbb6-4a6f-b3ee-9ea7184feca0" />
<img width="1920" height="1017" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/8bc5bb4b-9ab5-415c-bb65-306aaede941f" />
<img width="1920" height="1014" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/d3dae4d3-47c2-44a6-915d-1e2d5d57bccc" />
<img width="1920" height="654" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/1c0f5c68-4c89-467c-8bff-56f0f1e1eec2" />
<img width="1920" height="1004" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/985dd1b6-9c96-4aa6-93c9-5232c99d667a" />
<img width="1920" height="1004" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/1e0ad4d3-4857-4a3b-9495-e454b8db1a38" />
<img width="1920" height="833" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/2de77c4a-f87c-40eb-8808-d58911126f4b" />

---

**📜 License**                                                                                                                                                                                                    
This project is licensed for academic and personal use. Contributions welcome!

---

**👤 Author**                                                                                                                                                                                                     
S Anjum                                                                                                                                                                                                            
Final Year Data Science Engineering Student                                                                                                                                                                        
GitHub: @SyedaAnjumDS                                                                                                                                                                                              
