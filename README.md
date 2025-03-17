# API Development and Spend Analytics

This project demonstrates how to develop an API for **Spend Analytics** and **Marketing Attribution** using **FastAPI** and **Python**. The API allows users to input spend data for different traffic sources and calculates key marketing metrics, including:

- **Total Spend**
- **Total Conversions**
- **Cost per Conversion (CPC)**
- **Attribution Scores** based on spend proportion
- **Visualization** of spend vs. attribution in a combined chart

Additionally, the API provides an endpoint to simulate the marketing attribution model.

## Features

- **Spend Analytics**: Computes total spend, conversions, and cost per conversion.
- **Marketing Attribution Model**: Calculates attribution scores based on spend proportion.
- **API**: Developed using **FastAPI** to accept input data and return analytics.
- **Visualization**: Provides a plot of spend vs. attribution, allowing for better insights into marketing strategies.
- **Easy Setup**: Can be easily tested locally with **Uvicorn** and **FastAPI**.

## Installation

### Prerequisites
- Python 3.x (preferably 3.7 or later)
- pip (Python package installer)

### Steps to Install
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/spend-analytics-api.git
   cd spend-analytics-api
