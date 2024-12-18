# Personal Expense Tracker

A **Personal Expense Tracker** built using **Python** and **Flask** to help users manage their daily expenses efficiently. The application supports categorizing expenses, visualizing spending patterns, and sending email updates.

---

## Features

- Add, edit, and delete expense entries.
- Categorize expenses (e.g., food, travel, shopping).
- View expense summary and statistics.
- Email notifications for expense reports.
- Mobile-friendly UI.

---

## Installation

### Prerequisites
- Python 3.8 or later
- pip (Python package manager)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/python-flask--personal-expense-tracker.git
    cd python-flask--personal-expense-tracker/personal_expense_ttracker
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application:
    ```bash
    python app.py
    ```
4. Open your browser and navigate to `http://127.0.0.1:5000/`.

---

## Docker Support

The project includes a `dockerfile` for containerized deployment.

1. Build the Docker image:
    ```bash
    docker build -t expense-tracker .
    ```
2. Run the Docker container:
    ```bash
    docker run -p 5000:5000 expense-tracker
    ```

---

## Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Submit a pull request with detailed changes.

---

### Author

Created by K.Vamsi.
