# Flight Price Prediction

A web-based machine learning application that predicts flight prices based on user input. This project uses Flask for backend, CatBoost for the prediction model, and Streamlit for interactive data visualization.

### Developed by: Vigneshwar B. ([GitHub - vigneshwar](https://github.com/Vigneshwar-B))


![output](https://user-images.githubusercontent.com/104056311/211298522-27cc33ec-e4e4-4959-824c-3267d9827fd2.png)

---

## Project Structure

```
├── static/css                  # CSS files for styling
├── templates                   # HTML templates for rendering pages
├── Data_Train.xlsx             # Training dataset
├── Test_set.xlsx               # Test dataset
├── FlightPrice 4.ipynb         # Jupyter notebook for model training and experimentation
├── code_notebook.ipynb         # Additional notebook with insights and data analysis
├── app.py                      # Main Flask app file for API routing and handling requests
├── build.py                    # Script for model building and training
├── model.pkl                   # Serialized model file
├── requirements.txt            # List of Python packages and dependencies
├── README.md                   # Project documentation
├── Heroku_streamlit_STEPS.pdf   # Guide for deployment on Heroku
├── project report-vignesh.pdf   # Project report
└── output.png                  # Image of output for reference
```

## Requirements

Install dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Libraries and Frameworks Used

- **Flask** for building web APIs
- **CatBoost** for building the machine learning model
- **Pandas & Numpy** for data processing
- **scikit-learn** for model evaluation
- **Streamlit** for interactive visualization (optional)

## Model Training

The model was trained using data from `Data_Train.xlsx` with features such as departure time, arrival time, total stops, airline, and other relevant data points to predict flight prices.

The notebook `FlightPrice 4.ipynb` contains the data preprocessing steps, model training, and evaluation.

## Web App

The web app is implemented using Flask. The `app.py` file handles the routing and prediction API. When the user submits flight details (like airline, total stops, source, destination, and timings), the app returns a price prediction.

- **Homepage** (`/`): User input page for flight details
- **Predict Page** (`/predict`): Predicts the flight price based on the input

### Running the App

To run the app locally, use:

```bash
python app.py
```

The app will be available at `http://127.0.0.1:5000`.

## Deployment

Deployment instructions for Heroku are provided in `Heroku_streamlit_STEPS.pdf`.

---
