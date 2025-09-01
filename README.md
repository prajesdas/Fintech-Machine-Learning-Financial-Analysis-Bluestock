
# Bluestock Fintech – Machine Learning Financial Analysis

## Overview
This project fetches financial data such as **Balance Sheet**, **Profit & Loss**, and **Cash Flow** statements from an API, processes the data using **Machine Learning techniques**, and provides actionable financial insights. The results are stored in a **MySQL database** and displayed in **real-time** via the terminal and a **web interface**.

---

## Features
- Fetches financial data from APIs (Balance Sheet, P&L, Cash Flow)
- Preprocessing and feature engineering for ML analysis
- Machine Learning models for trend analysis and predictions
- Stores processed data and insights in MySQL
- Real-time visualization via:
  - Command-line dashboard
  - Web-based dashboard

---

## Tech Stack
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn, Flask/Django
- **Database**: MySQL
- **Version Control**: Git, GitHub

---

## Setup & Installation
```bash
# Clone the repository
git clone https://github.com/prajesdas/Bluestock-Fintech-Machine-Learning-Financial-Analysis.git

# Navigate into the project
cd Bluestock-Fintech-Machine-Learning-Financial-Analysis

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
````

---

## Usage

* Start the backend service to fetch and process data.
* Open the terminal to see live financial insights.
* Access the web interface at `http://localhost:5000` for visualization.

---

## Project Structure

```
├── data/               # Raw and processed financial data
├── models/             # Machine learning models
├── webapp/             # Web interface files
├── main.py             # Main execution script
├── requirements.txt     # Python dependencies
└── README.md           # Project documentation
```

---

## Future Enhancements

* Integration of advanced ML models (LSTM, Prophet) for forecasting
* Interactive charts and dashboards
* API for external integrations

---

## License

This project is licensed under the [MIT License](LICENSE).

```


```
