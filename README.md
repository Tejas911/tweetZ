# 📝 Sentiment Analysis Web App
![Sentiment Analysis Web App](ASSETS/5-Top-APIs-For-Sentiment-Analysis.webp)

## 🔍 Overview
In this project, I've developed a sophisticated sentiment analysis model tailored specifically to categorize tweets into positive, neutral, or negative sentiments. Understanding the importance of deciphering public opinion and emotional nuances expressed on social media platforms, my model excels in capturing subtle sentiment variations. I've integrated this model into an intuitive Web Application using Gradio, allowing users to easily input tweets and receive instantaneous sentiment analysis results. 


## 📁 Working
![LLaMA2 7B](ASSETS/llama2 7b.png)
In this project, leveraging the power of LLaMA2 7B, I've engineered a cutting-edge sentiment analysis model finely tuned to classify tweets into positive, neutral, or negative sentiments with remarkable accuracy. Understanding the pivotal role of discerning public sentiment on social media, my model excels in capturing nuanced emotional tones.

## Evaluation Metrics
In evaluating the sentiment analysis model based on LLaMA2 7B architecture, key metrics such as accuracy, precision, recall, and F1 score were employed, alongside the examination of the confusion matrix. Leveraging a diverse dataset of tweets, the model demonstrated high precision and recall, indicating its proficiency in accurately classifying sentiments. The analysis highlighted the model's effectiveness in capturing nuanced sentiment variations, affirming its suitability for real-world sentiment analysis tasks.



## 🚀 Instructions for Local Execution

To run the Sentiment Analysis Web App on your local machine, follow these steps: 

1. **Clone the Repository**: Begin by cloning the project repository to your local machine using the command:
    ```bash
    git clone https://github.com/FarzadNekouee/Enhanced_MRI_Tumor_Classification_Web_App.git
    ```

2. **Navigate to the Project Directory**: Change into the project directory:
    ```bash
    cd Enhanced_MRI_Tumor_Classification_Web_App
    ```

3. **Download the Pre-trained Model**: The pre-trained model is available on Google Drive. Download it by clicking [here](https://drive.google.com/file/d/1YAYTEHoAS0xkPjw_IJpvxsngHjyd5ST6/view?usp=sharing) and place it in the `model` directory within the cloned repository.

4. **Prepare Docker Environment**: Verify that Docker is operational on your machine. To construct the Docker image for the app, execute the following command in your project directory:
    ```bash
    docker build -t mri-tumor-streamlit-app .
    ```
   In case you face any issues with Docker Hub access, such as a '403 Forbidden' error, first pull the base Python image using this command:
    ```bash
    docker pull python:3.9-slim
    ```
   Once the base image is successfully pulled, retry building the app image.
    
5. **Run the Streamlit App**: Start the Streamlit app in a Docker container by executing the following command:
    ```bash
    docker run -p 8080:8080 mri-tumor-streamlit-app
    ```
    Note: Replace `8080` with your preferred port if necessary.

6. **Access the Web App**: Open your web browser and visit `http://localhost:8080` to interact with the MRI Brain Tumor Classification Web App. A demo of the app in action is available below:



![Web App Demo](demo.gif)

Enjoy exploring the app and classifying tweets!

## 🔗 Additional Resources

- 🌐 **Kaggle Notebook**: Interested in a Kaggle environment? Explore the notebook 
- 🌐 **Dataset Source**: Available on 
- 🤝 **LLM**: Hugging Face - LLaMA2 7B 
