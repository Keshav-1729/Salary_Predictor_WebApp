# Web Application Using Streamlit

This Project involves the use of streamlit ,  pandas , numpy , matplotlib and pickle to create a web application whose main aim is to predict the salary of the Software developer (per annum).
Firstly, the dataset is  loaded, then data pre-processing and Exploratory Data Analysis is carried out using pandas and matplotlib in order to make data appropriate for the model.

Later on, we move on to use a few regression models to use the one with the lowest error.The model which turned out the best performer was the decision tree, Using pickle to save the model in order to deploy it in the web application.

Now, moving on to using the streamlit module in order to create the frontend of the application.Used Pickle to load the saved model to use it in prediction.

The web application is comprised of 2 pages namely, Predict and Explore page. Explore page shows the data in pictorial representation which is used in order to train the model whereas the predict page uses the input information by the user for the prediction. To facilitate the switch between the pages, we used if else statement to import the required function to call and display.
 ## requirements.txt creation
 to  create use: 'pip free > requirements.txt'
