# Smart Registration Portal

A modern, responsive and user-friendly registration web application built using **HTML, CSS and JavaScript**. The application provides real-time form validation, password strength checking, a dynamic progress indicator, and Light/Dark theme options to deliver a smooth user experience.

## 📌 Project Overview

The Smart Registration Portal is designed to provide users with a simple and secure-looking registration interface. It validates user information before accepting form submission and displays appropriate error messages for invalid inputs.

The project focuses on responsive design, user-friendly interactions, form validation and clean code organization.

## ✨ Features

- **Responsive Design:** Works on desktop, tablet and mobile devices.
- **Light and Dark Mode:** Allows users to switch between light and dark themes.
- **Form Validation:** Displays error messages below corresponding fields.
- **Full Name Validation:** Ensures the user enters a valid name.
- **Age Validation:** Accepts ages between 18 and 100.
- **Email Validation:** Checks the email address format.
- **Mobile Number Validation:** Validates 10-digit Indian mobile numbers.
- **Password Validation:** Requires at least 8 characters, including uppercase, lowercase, numbers and special characters.
- **Confirm Password:** Checks whether both passwords match.
- **Password Visibility:** Allows users to show or hide passwords.
- **Password Strength Indicator:** Displays weak, medium or strong password status.
- **Form Completion Progress:** Dynamically updates the progress bar as users fill in the fields.
- **Success Message:** Displays a success message after successful validation.
- **Theme Persistence:** Remembers the selected theme using browser localStorage.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the registration page |
| CSS3 | Styling, layouts and responsive design |
| JavaScript | Form validation and interactive functionality |
| LocalStorage | Saving the selected theme |

## 📂 Project Structure

```text
smart-registration-portal/
│
├── index.html
│
├── style.css
│
├── script.js
│
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

- Visual Studio Code
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Live Server extension in VS Code (recommended)

### Installation and Execution

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Navigate to the project folder**

```bash
cd smart-registration-portal
```

**Step 3: Open the project in VS Code**

```bash
code .
```

**Step 4: Run the application**

1. Open `index.html` in VS Code.
2. Right-click the file.
3. Select **Open with Live Server**.
4. The registration portal will open in your browser.

Alternatively, open `index.html` directly in your browser.

## 📋 Form Validation Rules

| Field | Validation Requirement |
|---|---|
| Full Name | Must not be empty and must contain at least 2 non-space characters |
| Age | Must be a whole number between 18 and 100 |
| Email | Must follow a valid email format |
| Mobile Number | Must contain 10 digits and start with 6, 7, 8 or 9 |
| Password | Minimum 8 characters with uppercase, lowercase, number and special character |
| Confirm Password | Must match the original password |

All fields are mandatory.

## 🎨 User Interface

The application provides:

- Clean and modern registration card.
- Professional charcoal-colored logo.
- Consistent typography and spacing.
- Teal-themed interactive elements.
- Light and dark background options.
- Mobile-friendly form layout.
- Clear validation and success messages.

## 🧪 Testing

The following scenarios can be tested:

1. Submit the form without entering any information.
2. Enter an age below 18 or above 100.
3. Enter an invalid email address.
4. Enter an invalid mobile number.
5. Enter a weak password.
6. Enter different passwords in the password and confirmation fields.
7. Enter valid information in all fields.
8. Switch between light and dark themes.
9. Test the application on different screen sizes.

## 👥 Team Contributions

This project was developed collaboratively by a team of four members.

| Team Member | Responsibility |
|---|---|
| Member 1 | HTML structure and registration form |
| Member 2 | CSS styling and responsive design |
| Member 3 | JavaScript form validation |
| Member 4 | Theme switching, password features, testing and integration |

*Replace these roles with the actual contributions of each team member.*

## 🔮 Future Enhancements

- Backend integration using Python/Django or Node.js.
- Database integration for storing registration details.
- Email verification using OTP.
- Secure user authentication and login.
- User profile management.
- Server-side validation.

## ⚠️ Project Limitations

This is currently a frontend-only application. It performs client-side validation and displays a success message but does not create user accounts or store registration details in a database.

For production use, backend validation, secure password handling and database integration are required.

## 👩‍💻 Developed By

**Project Name:** Smart Registration Portal

**Technologies:** HTML5, CSS3, JavaScript

**Project Type:** Frontend Web Development



---

⭐ If you find this project useful, consider giving the repository a star!
