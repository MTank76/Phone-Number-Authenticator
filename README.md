# Phone-Number-Authenticator
A simple Django-based Phone Number Authenticator developed during my early learning days with Django. This project allows users to verify their phone numbers via Password authentication, ensuring secure user registration and login processes. It served as a foundational experience in working with Django forms, models, and views.

## Requirements
- Python 3.8 or higher
- Django 4.0 or higher
- SQLite3 (included with Python)
  
## Key Features
- **Phone Number Authentication**: Secure login via phone numbers instead of usernames.
- **Django Admin Integration**: Easily manage user authentication through the Django Admin Panel.
- **SQLite3 Database**: Uses SQLite3 for lightweight and efficient data storage.

## Deployment Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Phone-Number-Authenticator.git
   cd  newton
   ```
2.  **Apply Migrations**:
    ```bash
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```
3.  **Run the Server**:
    ```bash
    python3 manage.py runserver
    ```
4. **Access the application:**

   Open your web browser and go to `http://127.0.0.1:8000` to start using Authenticator.


## Contributing

If you'd like to contribute to Task Master, please fork the repository and submit a pull request with your changes. For bug reports or feature requests, open an issue on GitHub.
