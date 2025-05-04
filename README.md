 
/* Hospital Managment System */
Name: Zain Javed & Annas Abbas
Roll Number: 2023-uam-1903 & 2023-uam-1889
Subject Name: Database Systems
Project Name: Hospital Management System
Submission Date:21-5-2025
Submitted To:Mr.Shah Zaib










	Introduction
This document provides a detailed overview of the database structure designed for the Hospital Management System. The database is intended to manage patients, doctors, appointments, medical records, departments, and billing information.
	Database Structure
Database Name: Hospital_Managment_System
	Tables Description
	Patients Table 
Stores patient information including first name, last name, date of birth, gender, contact information, address, admission date, and discharge date.
	Doctors Table 
Contains details of doctors such as first name, last name, specialization, and department ID.
	Departments Table 
Maintains information about hospital departments including department name and location.
	Appointments  Table 

Manages appointment records between patients and doctors with appointment date, time, reason, and status.
	MedicalRecords Table 
Holds medical details for patients including diagnosis, treatment, prescription, and record date.
	Billing Table 
Handles billing information for patients, including the bill date, total amount, payment status, and services description.
	Relationships
	The database implements referential integrity using foreign keys:
	Appointments table references Patients and Doctors.
	MedicalRecords table references Patients and Doctors.
	Billing table references Patients.


	Conculsion
The Hospital Management System database has been carefully designed to ensure efficient management of hospital operations. It supports vital activities such as patient management, doctor management, appointment scheduling, maintaining medical records, and billing.







