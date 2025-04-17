# hospital-management-sys
Hospital management system using c++
Overview
This is a console-based Hospital Management System developed in C++. It allows hospital administrators to manage patient records, assign doctors, and handle room allocations. The system supports functionalities like adding, viewing, searching, and deleting patient records, as well as displaying available doctors.

⚙️ Features
Add Patient: Register new patients with details such as ID, name, age, disease, contact, and room requirements.

View Patients: Display a list of all registered patients along with their details.

Search Patient by ID: Retrieve patient information using their unique ID.

Delete Patient: Discharge a patient and record the discharge time.

Show Doctor List: View a list of available doctors with their specialties and fees.

Room Allocation: Automatically assign room numbers to patients requiring admission.

Bill Calculation: Calculate total bills based on doctor fees and room charges.

🧩 Design & Structure
Doctor Class: Represents a doctor with attributes like ID, name, specialty, fee, and seniority status.

Patient Class: Represents a patient with attributes like ID, name, age, disease, contact, room requirements, assigned doctor, and total bill.

HospitalManagementSystem Class: Manages the overall system, including patient and doctor records, and provides functionalities for adding, viewing, searching, and deleting patients.

🛠️ Requirements
C++ compiler (e.g., GCC, Clang)

Standard C++ libraries
