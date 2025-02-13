# ***STREAM : ML***

## **INNOVIZE Round 1**

#### Fitness & Lifestyle Prediction Model

*Prototype by AI Devilops*

*Solution built-up by Deepak Kaura (Team Lead)*

### **Problem Statement : -**

In today’s world, maintaining a healthy lifestyle is crucial for overall well-being. Your task is to build a machine learning model that predicts whether an individual is healthy or not based on the different physical and lifestyle attributes. You are provided with a dataset containing 6,000 entries of individuals, each with attributes like physical fitness level, diet preferences, activity level, sleep habits, mindfulness, and career. The goal is to train a model that accurately predicts the is_healthy label (1 for healthy, 0 otherwise).

Can your model differentiate between healthy and unhealthy person correctly? Let’s find out!

---------------------------------------------------------
### Approach to Building a Strong Classification Model:  
1. **Handling Missing Values:**  
   - Used **mode** for categorical features:  
     - **Diet preferences**  
     - **Activity level**  
     - **Career**  
     - **Gender**  
   - Used **mean** for numerical features:  
     - **Physical fitness level**  
     - **Average daily steps**  
     - **Daily average calories**  

2. **Outlier Treatment:**  
   - Applied the **Interquartile Range (IQR) method** to handle outliers in:  
     - **Daily average calories**  

3. **Encoding Categorical Features:**  
   - Utilized **Label Encoding** to convert categorical features into numerical form for model compatibility.  


### **Model results :-**

**HistGradientBoostingClassifier Accuracy: 98.58%**

-----------------------------------------------------
![image](https://github.com/user-attachments/assets/80199072-6e78-447f-b74b-4020cea5a340)
![image](https://github.com/user-attachments/assets/4af77dfd-a1b7-4215-8dde-5198e0b1fbcf)
