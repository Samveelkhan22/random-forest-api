# Random Forest Prediction API

This project implements a **Random Forest Regression model** and deploys it as a **RESTful API** using **FastAPI**. The API allows users to input features and receive predictions from the trained Random Forest model. It is hosted via **Ngrok** for testing purposes.

---

## Features
- **Model Deployment**: Deploys a pre-trained Random Forest model (`random_forest_model.pkl`) using FastAPI.
- **POST Request Support**: Accepts feature inputs in JSON format and returns predictions.
- **Ngrok Integration**: Enables public access to the API endpoint for testing.
- **Reusable Framework**: Easily adaptable to other machine learning models.

---

## Requirements

Install the following dependencies before running the app:

- Python 3.8 or higher
- FastAPI
- Uvicorn
- scikit-learn
- pydantic
- ngrok (optional, for public access)

---

## API Endpoint
- POST /predict/

---

## Testing the API
- Use a tool like `Postman` or `curl` to test the API.


