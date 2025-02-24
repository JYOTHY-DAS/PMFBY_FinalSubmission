# PMFBY Farmers' Contribution Forecasting

## Overview
This project aims to forecast farmers' contributions to the **Pradhan Mantri Fasal Bima Yojana (PMFBY)** using historical crop insurance data. By analyzing past patterns, the model provides insights into contribution trends, optimizing subsidy allocation and enhancing transparency in policy-making.

## Objective
- Forecast farmers' contributions to PMFBY using historical data on crop insurance coverage.

## Use Cases
- Identify patterns and trends in farmers' contributions.
- Optimize subsidy allocation for maximum coverage and equity.
- Enhance transparency and decision-making in policy design.

## Dataset
The dataset contains historical records related to PMFBY, including information on insured crops, subsidy status, sum insured, and farmers' contributions.

## Methodology
1. **Data Preprocessing:** Cleaning and transforming data for analysis.
2. **Exploratory Data Analysis (EDA):** Visualizing trends and patterns.
3. **Feature Engineering:** Selecting and creating relevant features.
4. **Model Selection:** Training and evaluating predictive models.
5. **Deployment:** Deploying the final model as an interactive web application using Flask.

## Technologies Used
- **Python** (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`)
- **Flask** (For web application deployment)
- **Machine Learning Models** (Regression-based models for forecasting)
- **GitHub Pages / Heroku / Render** (For hosting the web app, if applicable)

## Model Deployment
The final model is deployed using **Flask** and **Streamlit** allowing stakeholders to interactively explore predictions. The web application takes user inputs, processes them, and returns forecasted farmers' contributions.

## Project Structure
```plaintext
PMFBY-Forecasting/
│── Data/                  # Dataset files
│── notebooks/             # Jupyter notebooks for EDA and modeling
│── Report/                   # Source code for data processing and modeling
│── requirements.txt       # Dependencies
│── app.py                 # Flask main application script
│── README.md              # Project documentation
```

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PMFBY-Forecasting.git
   cd PMFBY-Forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```bash
   python app.py
   ```
4. To open the web application in your browser: [Click here](https://appfinalgit-cph2b5eex9z2rmkwqpjnfh.streamlit.app/)

## Results and Insights
- Key patterns in farmers' contributions were identified.
- The model provides accurate forecasts for better subsidy allocation.
- The web application enables real-time interaction with predictions.

## Future Enhancements
- Incorporate more advanced ML models for improved accuracy.
- Add a dashboard for visual analytics.
- Extend the dataset with additional features for deeper insights.

## Contributing
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For any questions or feedback, feel free to reach out!

📧 Email: jyothydas11@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jyothy-das/) 

