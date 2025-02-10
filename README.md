# 🩸 BloodBridge - Connecting Donors & Patients

## 📌 Project Overview
The **Blood Bank Management System** is a web-based platform that facilitates blood donation and availability tracking. It allows users to register as donors, search for available blood groups, and contact donors directly if blood is not available in the blood bank. This system improves the efficiency of blood donation and helps save lives by providing a quick way to find blood donors.

## 🚀 Features
- **🔗 Donor Registration:** Users can sign up to donate blood and provide their contact details.
- **🩸 Blood Availability Search:** Find blood groups in nearby blood banks.
- **📞 Donor Contact Information:** If blood is unavailable, users can contact donors directly.
- **📅 Blood Donation Scheduling:** Enables users to set donation appointments.
- **🔐 Secure Authentication:** Registered users can log in to manage their profiles.
- **📨 Request Blood:** Users can request specific blood types when needed.

## 📁 Project Structure
```BloodBankManagement/
│── **final.html**            → Main Homepage
│── **message.html**          → Login Page
│── **register.html**         → Registration Page
│── **why_donate.html**       → Importance of Blood Donation
│── **who_can_give.html**     → Eligibility Criteria
│── **contact_us.html**       → Contact Page
│── **refer_friend.html**     → Refer a Friend Page
│── **donate_where.html**     → Find Nearby Blood Banks
│── **feedback.html**         → User Feedback Form
│── **assets/**               → Contains images, stylesheets, and scripts
│   ├── **css/**              → CSS files for styling
│   ├── **js/**               → JavaScript files for interactive elements
│   ├── **images/**           → Contains images and icons
│── **database.sql**          → MySQL Database Structure (if applicable)
│── **README.md**             → Documentation for the project
```

## 🏗️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP / Python (Django/Flask)
- **Database:** MySQL / Firebase
- **Hosting:** Apache / AWS / Heroku

## 🔧 Installation & Setup

### Prerequisites
- **For PHP Users:** Install XAMPP or WAMP Server.
- **For Python Users:** Install Python 3.x, Django/Flask.
- **For Database Users:** Install MySQL or Firebase.

### Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/blood-bank-management.git
   cd blood-bank-management

2. **For PHP Users:**

- Move the project folder to htdocs (XAMPP) or www (WAMP).
- Start Apache & MySQL from the control panel.
- Open the browser and navigate to:
http://localhost/blood-bank-management

 3.**For Python Users (Django/Flask):**

- Install dependencies:
  ``` pip install -r requirements.txt```
-Run migrations:
 ```python manage.py migrate```
- Start the server:
 ```python manage.py runserver```
- Open http://127.0.0.1:8000 in your browser.
