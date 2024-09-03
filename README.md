# Hospital-Management-System
This repository contains the SQL script for creating a comprehensive database schema designed for a Hospital Management System. The schema includes various entities such as patients, doctors, appointments, medical history, and more, providing a robust structure to manage healthcare operations.

Database Structure
The schema is organized into the following tables:

User Login (online_retail_app.user_login): Stores user login information, including user credentials and basic personal details.

Patient (hospital_management.patient): Contains patient details such as email, password, name, address, and gender.

Medical History (hospital_management.medical_history): Records patients' medical history, including past conditions, surgeries, and medications.

Doctor (hospital_management.doctor): Stores doctor information, including email, name, password, and gender.

Appointment (hospital_management.appointment): Manages appointment details such as date, start time, end time, and status.

Patient Visits (hospital_management.patient_visits): Logs patient visits, concerns, and symptoms, linked to the patient and appointment tables.

Schedule (hospital_management.schedule): Defines the schedule of doctors, including start time, end time, break time, and the day.

Patients History (hospital_management.patients_history): Associates patients with their respective medical history records.

Diagnose (hospital_management.diagnose): Stores diagnostic information and prescriptions provided by doctors during appointments.

Doctor Schedules (hospital_management.doctor_schedules): Links doctors with their schedules.

Doctor View History (hospital_management.doctor_view_history): Tracks which doctors have viewed specific medical histories.

Features
Comprehensive Data Relationships: The schema is designed to ensure that relationships between different entities are well-maintained through the use of foreign keys.

Normalization: The structure follows normalization principles to avoid data redundancy and ensure data integrity.

Scalability: The schema is designed to be scalable, allowing for future expansions to accommodate additional features or entities as needed.

How to Use
Database Initialization: Run the provided SQL script to initialize the schema within your PostgreSQL database.

Customization: Modify the schema as needed to fit the specific requirements of your hospital management system.

Integration: Integrate this schema with your hospital management application's backend to manage data effectively.

Contribution
Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements or additional features.
