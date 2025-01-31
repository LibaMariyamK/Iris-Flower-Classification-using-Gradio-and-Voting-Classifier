# **Iris Flower Classification using Voting Classifier and Gradio**  

## **Overview**  
This project builds an **Iris Flower Classifier** using a **Voting Classifier** that combines multiple machine learning models. The trained model is deployed using **Gradio**, providing an interactive web interface for predictions.  

## **Features**  
- Uses **17 machine learning models** in an ensemble (Voting Classifier).  
- Predicts the class of an **Iris flower** based on **sepal and petal dimensions**.  
- Provides a **user-friendly web interface** using **Gradio**.  

## **Technologies Used**  
- **Python** (Data Processing & Model Training)  
- **Scikit-Learn** (ML Models & Voting Classifier)  
- **XGBoost, LightGBM, CatBoost** (Advanced ML Models)  
- **Gradio** (Web UI for Model Deployment)  
- **Pickle** (Model Serialization)  
 

## **How It Works**  
1. The dataset (**iris.csv**) is loaded and preprocessed.  
2. A **Voting Classifier** is trained using **20 different models**.  
3. The trained model is saved using **Pickle**.  
4. A **Gradio interface** is created for user interaction.  
5. Users enter **flower measurements**, and the app predicts the **Iris species**.  

## **Usage**  
- Open the Gradio UI in the browser.  
- Enter **sepal length, sepal width, petal length, and petal width**.  
- Click **Submit** to get the predicted **Iris class**.  

## **Example Output**  
```
Input: Sepal Length = 5.1, Sepal Width = 3.5, Petal Length = 1.4, Petal Width = 0.2  
Prediction: setosa  
```  

## **Why Use Pickle?**  
- **Pickle** is used to save the trained model, so we don’t need to train it every time the script runs.  
- The model is loaded from the file when making predictions.  

## **Why Use Gradio?**  
- **Gradio** makes it easy to build a simple **web UI** for the model.  
- Users can interact with the model **without writing code**.  
- The `gr.Interface` function defines **inputs, outputs, and UI layout**.  

## **License**  
This project is open-source and free to use.  
