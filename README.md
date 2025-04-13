# 🏥 Hospital Management System  
**A Web-Based Hospital Management System using PHP, MySQL, and Bootstrap**

---

## ✨ Features to be Implemented

1. Doctors should have the ability to accept or reject appointments, notifying patients accordingly.
2. Prevent duplicate registrations by checking for existing email addresses.
3. Encrypt user passwords and hide them from the admin panel view.
4. Add pagination across all list views for better usability.
5. Fix bug in billing: prevent duplicate entries for patients visiting the same doctor multiple times.
6. Expand prescription details to include more specific medical data.
7. Enhance payment records with fields like payment date, amount paid, etc.
8. Implement data export (Excel) functionality in the admin panel.

---

## 🧰 Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) Web Server
- Code Editor (VS Code, Sublime Text, etc.)
- Modern Web Browser (Google Chrome, Firefox, etc.)

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache via XAMPP  
- **PDF Generation:** TCPDF  
- **Scripts:** JavaScript  

---

## 🚀 How to Run This Project

1. Install XAMPP and start Apache & MySQL via the XAMPP Control Panel.
2. Clone or download this repository.
3. Move the extracted folder to `htdocs` inside your XAMPP installation directory.
4. Launch `phpMyAdmin` (go to `localhost/phpmyadmin` in browser).
5. Create a new database named `myhmsdb`.
6. Import the `myhmsdb.sql` file into this database.
7. Open your browser and go to `localhost/foldername`.
8. 🎉 You're all set!

---

## 💻 Project Modules Overview

### 👨‍⚕️ Patient Module

- Register/Login as a patient.
- Book appointments with doctors.
- View appointment history.
- Cancel appointments (status gets updated for both patient & doctor).

### 🩺 Doctor Module

- Login access provided by admin.
- View upcoming appointments.
- Search appointments by patient contact number.
- Cancel appointments (status reflected in patient view).

### 🔐 Admin Module

- Admin login: `admin` / `admin123`
- View & manage patient and doctor records.
- Add/remove doctors.
- View and manage appointments.
- View feedback from users (Contact page).
- Export data (To be implemented).
- Passwords (To be encrypted and hidden from UI).

---

## 🔄 Recent Updates

### ✅ Appointment Cancellation

- Patients and doctors can cancel appointments.
- Status like “Deleted by you” is shown in the dashboard accordingly.

### 🗑️ Doctor Removal (Admin)

- Admin can now remove doctor profiles directly from the system.

---

## 📸 Screenshots

> ![Dashboard Screenshot](https://user-images.githubusercontent.com/36665975/66570841-03032f80-eb8c-11e9-9cfc-62b6b869c918.png)  
> *Admin Dashboard*

> ![Patient Registration](https://user-images.githubusercontent.com/36665975/66570027-5b393200-eb8a-11e9-9e97-088630b5e583.png)  
> *Patient Registration Form*

> ![Doctor View](https://user-images.githubusercontent.com/36665975/66570704-be779400-eb8b-11e9-92ae-21d8e0e4aba4.png)  
> *Doctor's Appointment Dashboard*

---

## 🖥️ Environment Used

- OS: Ubuntu 19.04
- Server: XAMPP with Apache2 and MySQL
- Browser: Google Chrome 77.0+

---

## 📬 Contact

For feedback or suggestions, feel free to reach out via the ‘Contact’ page on the website.

---

Let me know if you want this as a downloadable `.md` file or want me to help update your actual GitHub repo with this!
