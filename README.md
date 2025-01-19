# Budget Tracker

A simple **Budget Tracker** application built using Django and Django REST Framework (DRF). This project allows users to manage their income and expenses effectively, view financial reports using visual charts, and set monthly budgets with warnings for over-expenditure.

---

## Features

- **Income and Expense Management**:
  - Add, update, and delete income and expense records.
- **Financial Reports**:
  - View income and expenses in a visual doughnut chart.
- **Monthly Budget Setting**:
  - Set a monthly budget and receive warnings if exceeded.
- **Responsive Design**:
  - Clean UI with Bootstrap for a modern and responsive design.

---

## Technologies Used

### Backend:
- Django (Web framework)
- Django REST Framework (API development)

### Frontend:
- HTML5, CSS3
- Bootstrap 5 (Responsive design)
- Chart.js (Data visualization)

### Database:
- SQLite (default Django database)

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- Python (3.8+)
- pip (Python package manager)
- Virtualenv (optional but recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/budget-tracker.git
   cd budget-tracker
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Access the application at:
   ```
   http://127.0.0.1:8000/
   ```

---

## API Endpoints

The application provides a RESTful API for managing budgets. Below are the available endpoints:

### Income Endpoints:
- `GET /api/incomes/` - List all income records
- `POST /api/incomes/` - Create a new income record
- `PUT /api/incomes/{id}/` - Update an existing income record
- `DELETE /api/incomes/{id}/` - Delete an income record

### Expense Endpoints:
- `GET /api/expenses/` - List all expense records
- `POST /api/expenses/` - Create a new expense record
- `PUT /api/expenses/{id}/` - Update an existing expense record
- `DELETE /api/expenses/{id}/` - Delete an expense record

### Budget Endpoints:
- `GET /api/budgets/` - List all budget records
- `POST /api/budgets/` - Create a new budget record
- `PUT /api/budgets/{id}/` - Update an existing budget record
- `DELETE /api/budgets/{id}/` - Delete a budget record

---

## Running Tests

To run unit tests, use the following command:
```bash
python manage.py test
```

Make sure all tests pass successfully to ensure your application is working correctly.

---

## Improvements to Consider

1. **Authentication:**
   - Add user authentication to allow multiple users to manage their budgets securely.

2. **Advanced Charts:**
   - Introduce line or bar charts for tracking trends over time.

3. **Notifications:**
   - Send email or SMS alerts when nearing or exceeding the budget.

4. **Deployment:**
   - Deploy the application on a platform like Heroku or AWS.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

---

## Contact

If you have any questions, feel free to reach out:
- **Email:** Shahryarmashouf.1998@gmail.com
