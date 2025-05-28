# Expense Management System

* This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.
* Expense Tracking System to help users manage their finances efficiently.


## Project Structure

expense-tracking-system/

- **frontend/**: Streamlit-based UI (app.py)
- **backend/**: FastAPI backend logic (server.py)
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
2. **Install Python dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
3. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
4. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
