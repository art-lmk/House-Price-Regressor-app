# House-Price-Regressor-app
-This app predicts the price of a certain house based on 3 criterias:
 1. Average no. of Rooms(RM)
 2.  Lower Status Population(LSTAT)
 3.  PTRATIO(Parent-Teacher ratio)
- The only target variable being used is
1. Median Value(MEDV)
Multiple independent variables are used to predict the dependent variable. Therefore, the model used here is MulipleLinearRegression model. This model has been built and trained and can be accessed via the follwing link(https://af06480766b8.ngrok-free.app/)
NB: If you clone this repository, you will have the code but will need to set up your own NGROK_TOKEN in your environment (e.g., in your own Colab secrets manager or as environment variables) for the code that uses those secrets to run successfully.


This project addresses the problem of providing a quick and accessible estimate of a property's potential market value based on specific, measurable characteristics(average no.of rooms, pupil-teacher ratio,lower-status population).

Think of it this way:

For potential buyers or sellers- It offers a handy tool to get a data-driven ballpark figure for a house's price without needing to consult an expert immediately.
For real estate professionals- It can serve as a preliminary tool for evaluating properties or generating leads.
It essentially provides a convenient way to leverage data and machine learning to gain insight into property valuation, making the process more transparent and accessible for informed decision-making.


Explore the Multiverse- Use the sliders to define the characteristics of a house in a new universe.

Run the Prediction- The model will use its interdimensional equation to compute a stable price.

Analyze the Result- See how the fundamental laws of real estate apply, no matter which dimension you're in!

🛠️ Built With
Python - The programming language of the multiverse.

Scikit-learn - The library containing the linear regression algorithm.

Streamlit - The framework for building the interactive web app.

Google Colab - The computational engine for model training.

Ngrok - The tunneling technology that bridges our dimension to the web.


