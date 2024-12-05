# Backend Authentication Website

## Overview
This project is a web-based authentication system built using Python's Flask framework. It provides a simple yet effective way to handle user registration, login, and session management. The project includes a visually appealing user interface and ensures secure user authentication.

---

## Features

1. **User Registration:**
   - Allows new users to create an account with a username and password.

2. **User Login:**
   - Authenticates users using their credentials.
   - Provides feedback for incorrect login attempts.

3. **Session Management:**
   - Maintains user sessions after successful login.
   - Supports secure logout functionality.

4. **User Dashboard:**
   - Displays a personalized welcome message.
   - Includes a logout button for ending the session.

5. **Stylish Interface:**
   - Gradient background with centered content.
   - Responsive and visually appealing design for all pages.

---

## Technologies Used

1. **Backend:**
   - Flask (Python)
2. **Frontend:**
   - HTML5
   - CSS3 (with gradient styling and responsive design)
3. **Session Management:**
   - Flask sessions
4. **Deployment:**
   - Run locally using Flask's development server

---

## File Structure

```plaintext
project/
├── static/
│   └── styles.css           # Stylesheet for all pages
├── templates/
│   ├── login.html           # Login page template
│   ├── register.html        # Registration page template
│   └── dashboard.html       # Dashboard template for logged-in users
├── app.py                   # Main Flask application file
├── requirements.txt         # Dependencies required for the project
└── README.md                # Documentation for the project
```

---

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Set Up Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```bash
   python app.py
   ```

5. **Access the Website:**
   Open a browser and navigate to `http://127.0.0.1:5000`.

---

## Usage

1. **Register a New User:**
   - Navigate to the "Register" page.
   - Enter a unique username and password to create an account.

2. **Login to Your Account:**
   - Navigate to the "Login" page.
   - Enter your registered username and password.
   - Upon successful login, you will be redirected to the dashboard.

3. **Logout:**
   - Click the "Logout" button on the dashboard to end your session.

---

## Screenshots

1. **Login Page:**
   - Gradient background with a centered login form. Allows user to enter Username and password
2. **Registration Page:**
   - Similar to the login page but allows new users to register.
3. **Dashboard:**
   - Personalized welcome message and a logout button.

---

## Future Enhancements

1. Add database integration for persistent user storage (e.g., SQLite, PostgreSQL).
2. Implement password hashing for enhanced security.
3. Extend the UI with additional pages and features.
4. Deploy the project using a production server (e.g., Gunicorn, Nginx).

---

## Acknowledgments
Special thanks to the open-source community for providing resources and tools that made this project possible.

---

## Contact
For any inquiries or issues, feel free to contact the project maintainer at [yugarakshinigs@gmail.com].

