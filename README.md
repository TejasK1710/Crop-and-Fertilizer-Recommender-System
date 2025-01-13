# Crop-and-Fertilizer-Recommender-System
The Crop and Fertilizer Recommender System is a machine learning-based web application designed to assist farmers in determining the best crop to grow and the optimal fertilizer to use based on soil and environmental factors. This project leverages data science, machine learning, and web development to provide actionable insights to users.

# Features

Predicts the most suitable crop for cultivation based on input parameters such as soil nutrients, pH, rainfall, and temperature.

User-friendly web interface built with HTML, CSS, and Flask.

Supports dynamic predictions and displays results in real-time.

Scalable and customizable for additional features like IoT sensor integration or region-specific advice.

# Technologies Used

Frontend: HTML, CSS

Backend: Flask (Python)

Machine Learning Model: Scikit-learn

Libraries:

Flask: Web framework for Python.

joblib: For saving and loading the trained ML model.

pandas, numpy: Data processing and manipulation.

scikit-learn: Machine learning library for model training.

# How to Use

Clone the repository:

git clone https://github.com/your_username/crop-fertilizer-recommender.git
cd crop-fertilizer-recommender

Install dependencies:

pip install -r requirements.txt

Run the Flask application:

python app.py

Open a browser and navigate to:

http://127.0.0.1:5000

Fill out the form with soil and environmental data to get crop recommendations.

# Input Parameters

The web application takes the following inputs:

District Name: Name of the district.

Soil Color: Options: Red, Black, Brown.

Nitrogen (mg/kg): Soil nitrogen content.

Phosphorus (mg/kg): Soil phosphorus content.

Potassium (mg/kg): Soil potassium content.

pH: Soil pH level (0 to 14).

Rainfall (mm): Average rainfall in the region.

Temperature (C): Average temperature in the region.

# Example Output

Predicted Crop: Wheat

File Structure

# project-directory/
    |- app.py               # Flask application
    |- templates/
        |- index.html       # HTML file for the web interface
    |- static/              # Static files (CSS, images, etc.)
    |- crop_fertilizer_model.joblib  # Trained ML model
    |- README.md            # Project documentation
    |- requirements.txt     # Python dependencies

# Requirements

Python 3.7+

Flask

Scikit-learn

Joblib

# Future Enhancements

Integrate real-time weather API to fetch rainfall and temperature data.

Add fertilizer recommendation functionality.

Provide crop yield predictions.

Mobile application version for easy accessibility.

# Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments

Special thanks to:

Open-source contributors.

Kaggle for providing relevant datasets.
