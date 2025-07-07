🏥 Eye Hospital Management System (Spring Boot)

A secure and scalable web-based application for managing operations of multiple eye hospitals. Built using Java, Spring Boot, and JWT authentication.

---

🚀 Features

1. 👥 Multi-Hospital Management
- Each hospital can register and maintain its own data.
- Data isolation between hospitals.
- Super Admin (optional) can view all hospitals.

2. 🧑‍⚕️ Role-Based Access
Admin – Manages doctors, patients, appointments, etc.
Doctor – Views appointments, manages prescriptions.
Patient– Books appointments, views prescriptions.
Super Admin– Manages all hospitals (optional).

3. 📦 Modules

- **Authentication**: Secure JWT-based login for all users.
- **Hospital Management**: Register hospitals, auto-create admin.
- **Doctor Management**: Add/edit/remove doctors with specialization.
- **Patient Management**: Full patient record handling.
- **Appointment System**: Book, cancel, or reschedule.
- **Prescription System**: Doctors write/view prescriptions.
- **Billing System**: Generate and track payments.
- **Reports**: Revenue, appointments, and doctor activity stats.

---

🛠️ Tech Stack

- **Backend**: Java 17, Spring Boot 3+
- **Security**: Spring Security, JWT
- **Database**: MySQL / H2 (development)
- **Tools**: Maven, Lombok (optional), MapStruct (optional)


---

## 🧪 Running the App Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eye-hospital-system.git
   cd eye-hospital-system


