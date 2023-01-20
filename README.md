# DDC
This project is a web application built with Django that uses machine learning to predict insulin dosage for patients with diabetes. The model for insulin-dependent patients was generated using the Bergman minimal model in Matlab, simulating the exercise as a disturbance that occurs in the morning before breakfast, and the meals were a disturbance that occurred three times a day.

# Getting Started
To get started with this project, you will need to have the following software installed on your machine:
```
Python 3.x
Django 3.x
Pip
Virtualenv (optional, but recommended)
Matlab (if you want to re-train the model)
```
# Installation

1. Clone the repository to your local machine
2. Navigate to the project directory
3. Create a virtual environment and activate it (if using virtualenv)
4. Run the migration command to create the necessary database tables
5. Start the development server

# Usage

Input your glucose levels and other relevant information.
The machine learning model will predict the insulin dosage for you.

# Built With
Django - The web framework used.
Scikit-learn - Machine learning library.
Matlab - Used to generate the insulin-dependent patients model using the Bergman minimal model.

# Authors
Esther Matamoros
