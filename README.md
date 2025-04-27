# Real_Estate_Price_Prediction
A machine learning-based web app that predicts house prices in Bengaluru based on location, area, and BHK details."
It helps users estimate house prices accurately and quickly!
The backend is built with Flask, and the frontend is a simple HTML , CSS and JS page.

---How it runs:
The backend server (Flask) hosts a machine learning model trained to predict house prices in Bengaluru.
The user interacts with a simple web page (frontend) by entering property details like location, area, BHK, and bathrooms.
The frontend sends this information to the backend, where the model processes the input and returns the predicted house price, which is then displayed on the webpage.

---How to Install and Run
Clone the repository or download the project files.
Install the dependencies:
#pip install -r requirement.txt
Start the Flask server:
cd Server
python app.py
Open Client/index.html in your web browser.

---External Libraries Used:
NumPy	-- Numerical operations
Pandas -- Data manipulation
scikit-learn	-- Machine learning model (training + prediction)
pickle	-- Saving/loading machine learning model
flask -- Backend web framework

Requirements
Python 3.8 or higher
All libraries listed in requirement.txt(pandas,numpy,scikit-learn,flask)
Basic browser (Chrome, Firefox)
