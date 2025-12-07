# Expense Management System

The Expense Tracking System is a lightweight yet powerful application designed to help users log, manage, and analyze their daily expenses with ease. It stores all entries in a structured database and provides insightful analytics to better understand spending habits over time. Whether you're keeping track of personal finances or exploring data-driven budgeting, this project offers a clean, efficient, and intuitive foundation to build on.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sai-9-data/Expense-Tracking-System.git
   cd Expense-Tracking-System
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py

   ```
