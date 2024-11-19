Clinic Management System
🏥 Overview
The Clinic Management System is designed to enhance clinic operations by efficiently organizing data for patients, appointments, billing, consultations, prescriptions, and staff management.

🎯 Objectives

Comprehensive patient data management.
Streamlined scheduling of appointments and consultations between patients and doctors.
Clear and accurate billing system.
Storage and tracking of medical prescriptions.
Improved management of clinic staff.
📊 Features

Patient Management
Store patient details such as name, medical history, and insurance provider.
Appointment Scheduling
Manage patient appointments by date, time, and reason for visit.
Billing System
Track invoices, payment statuses, and payment methods.
Consultation Records
Record medical consultations with reasons and doctor notes.
Prescription Tracking
Log prescriptions, dosages, and doctor instructions.
Staff Management
Maintain staff details, roles, and hire dates.
🗂️ Database Schema
The database is designed with the following tables:

Table: Patients
Column Name	Data Type	Description
patient_id	SERIAL	Unique patient ID
name_patient	VARCHAR	Patient name
contact_details	TEXT	Contact information
insurance_provider	VARCHAR	Insurance provider
medical_history	TEXT	Medical history
Table: Appointments
Column Name	Data Type	Description
appointment_id	SERIAL	Unique appointment ID
date_appointment	DATE	Appointment date
time_appointment	TIME	Appointment time
reason_visit	TEXT	Reason for visit
patient_id	INT	Patient ID (foreign key)
doctor_id	INT	Doctor ID (foreign key)
(Repeat this structure for other tables such as billing, consultations, prescriptions, and staff.)

