# Crop_Recommendation![Uploading Screenshot (79).png…]()

![Uploading Screenshot (79).png…]()


🌱 Description of the Application:
Title: "Crop Recommendation System"

Purpose: This system helps farmers or users determine the best crop to grow based on environmental conditions and soil nutrients.

Inputs:

Nitrogen

Phosphorus

Potassium

Temperature (°C)

Humidity (%)

pH level of the soil

Rainfall (mm)
🛠 Technologies Used:
Frontend:

HTML: For the structure of the webpage.

CSS: For styling (e.g., glassmorphism-style form, background image, button styles).

JavaScript (optional): For input validation or enhancements (not directly visible but commonly used).

Backend:

Python with Flask:

Used to handle form submission (/predict endpoint seen in the URL).

Uses a machine learning model (likely a DecisionTreeClassifier, based on the browser tab title error) to predict the best crop.

Machine Learning:

A trained model (like Decision Tree or Random Forest) that takes input features and returns a crop name.

The model is most likely trained using a dataset containing crop yield data under various environmental and soil conditions.

🌐 How it Works:
User enters all environmental and soil details in the form.

Upon clicking "Get Recommendation", the data is sent to the Flask backend at /predict.

Flask uses the ML model to compute and return a suitable crop.

The predicted crop is displayed dynamically on the screen.
