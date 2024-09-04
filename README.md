Sentiment Analysis with Flask and AWS EC2
=========================================

Project Overview
----------------

Developed a sentiment analysis model for movie reviews, including data preprocessing, feature engineering, and model selection. Applied Explainable AI tools like SHAP and LIME for model evaluation. Deployed the model via a Flask application and hosted it on AWS EC2 for scalable, global access.

Features
--------

-   **Data Preprocessing:** Cleaned and prepared movie review data for analysis.
-   **Feature Engineering:** Extracted relevant features for accurate sentiment prediction.
-   **Model Selection:** Chose the best model for sentiment classification.
-   **Explainable AI:** Used SHAP and LIME to interpret model predictions.
-   **Deployment:** Hosted the Flask application on AWS EC2, making it accessible globally.

Dataset
-------

The dataset used for this project can be found at [IMDB Dataset of 65K Movie Reviews](https://www.kaggle.com/datasets/crisbam/imdb-dataset-of-65k-movie-reviews-and-translation).

Setup and Running the Project
-----------------------------

1.  **Clone the Repository:**

    

    `git clone https://github.com/jayasampreethreddy/Sentiment-Analysis.git`

2.  **Navigate to the Project Directory:**

   

    `cd Sentiment-Analysis`

3.  **Install Dependencies:** Make sure you have Python 3 installed. Then install the required libraries using:

    

    `pip install -r requirements.txt`

4.  **Prepare the Dataset:** Download the dataset from Kaggle and place it in the appropriate directory as specified in the code.

5.  **Run the Application:** Start the Flask application with:

    

    `python3 awsengine.py`

6.  **Access the Application:** Once the server is running, you can access the application via your web browser at `https://ec2-13-60-188-30.eu-north-1.compute.amazonaws.com/`.

Usage
-----

-   Use the API endpoints provided by the Flask application to interact with the sentiment analysis model.


-   Use the API endpoints provided by the Flask application to interact with the sentiment analysis model.

Contributing
------------

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
