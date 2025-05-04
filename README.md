# Hospital Management System

![Muhammad Nawaz Shareef University of Agriculture Logo](MNS.png)

## Project Overview
This project is a **Hospital Management System** designed to efficiently manage hospital operations, including patient records, doctor details, appointments, medical records, and billing. It serves as a comprehensive database solution for healthcare institutions.

---

## Team Members
- **Zain Javed** (Roll Number: 2023-uam-1903)
- **Annas Abbas** (Roll Number: 2023-uam-1889)

**Subject:** Database Systems  
**Submitted To:** Mr. Shah Zaib  
**Submission Date:** 21-5-2025  

---

## Database Structure
**Database Name:** `Hospital_Managment_System`

### Tables Description
1. **Patients Table**  
   - Stores patient information:  
     `first_name`, `last_name`, `date_of_birth`, `gender`, `contact_info`, `address`, `admission_date`, `discharge_date`.

2. **Doctors Table**  
   - Contains doctor details:  
     `first_name`, `last_name`, `specialization`, `department_id`.

3. **Departments Table**  
   - Maintains department information:  
     `department_name`, `location`.

4. **Appointments Table**  
   - Manages appointment records:  
     `appointment_date`, `appointment_time`, `reason`, `status` (linked to Patients and Doctors).

5. **MedicalRecords Table**  
   - Holds medical details:  
     `diagnosis`, `treatment`, `prescription`, `record_date` (linked to Patients and Doctors).

6. **Billing Table**  
   - Handles billing information:  
     `bill_date`, `total_amount`, `payment_status`, `services_description` (linked to Patients).

---

## Relationships
- **Referential Integrity** is enforced using foreign keys:
  - `Appointments` table references `Patients` and `Doctors`.
  - `MedicalRecords` table references `Patients` and `Doctors`.
  - `Billing` table references `Patients`.

---

## Conclusion
The Hospital Management System database is meticulously designed to streamline hospital operations, ensuring efficient management of:
- Patient and doctor records.
- Appointment scheduling.
- Medical history tracking.
- Billing and payments.

For further details, refer to the full project report.
