# Energy Demand Forecasting Streamlit App

## Description

This Streamlit app aims to forecast energy demand using historical data and machine learning techniques. The app provides an interactive interface for users to input parameters and view the predicted energy demand.

## Setup Guide

### Prerequisites

- Python 3.x installed on your system
- Git installed on your system
- Docker installed (if you plan to use Docker)

### Local Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/PrepVector/Applied-ML.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Applied-ML
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

5. **Access the app in your browser at** `http://localhost:8501`

### Docker Setup

1. Make sure Docker is running on your system.

2. **Clone the repository:**

    ```bash
    git clone https://github.com/PrepVector/Applied-ML.git
    ```

3. **Navigate to the project directory:**

    ```bash
    cd Applied-ML
    ```

4. **Build the Docker image:**

    ```bash
    docker build -t energy-demand-forecasting-app
    ```

5. **Run the Docker container:**

    ```bash
    docker run -p 8501:8501 energy-demand-forecasting-app
    ```

6. **Access the app in your browser at** `http://localhost:8501`