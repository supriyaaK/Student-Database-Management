🎓 Student Database Management System (ServiceNow)

   LIVE DEMO:
 https://drive.google.com/file/d/1unaJRU5P5tJbcl22DBJAemYyfAjX4o9G/view?usp=drivesdk

📌 Overview

• The Student Management System is a ServiceNow-based application designed to efficiently manage student information, fee details, and academic progress.

• It streamlines the entire process of student admission, fee calculation, and performance tracking through automated workflows and user-friendly dashboards.


---

🚀 Features

• 🧑‍🎓 Student Information Management — Maintain complete student records including admission, personal, and guardian details.

• 💰 Automated Fee Calculation — Fees auto-calculated based on grade and installment type (quarterly or monthly).

• 📈 Progress Tracking — Track student performance across subjects and terms with auto-calculated percentages.

• ⚙ Automation — Workflows to reduce manual errors and improve data accuracy.

• 🔒 Field Control — Prevents manual modification of calculated fee and installment fields.


---

🧩 System Tables

Table Name   &                  	Description

Education (Base Table) ->	Stores core student details like admission number, name, grade, section, and status.

Admission	           ->  Stores guardian information, contact details, and admission data linked to the Education table.

Student Fee Details	  ->  Handles fee structure, installment types, and auto-calculation logic.

Student Progress       ->	Records marks, percentage, and remarks for each subject and term.



---

🔗 Relationships

• Education → Admission, Student Fee Details, Student Progress (Primary link)

• Admission → Contains student and guardian details.

• Student Fee Details → Calculates and stores fee installments based on grade.

• Student Progress → Tracks subject-wise marks, percentages, and teacher remarks.


---

🧮 Functionalities

1️⃣ Auto Fee Calculation

   • Fee populated automatically based on grade.

   • Quarterly/monthly installments auto-generated.


2️⃣ Student Admission Entry

   • Enter admission details, guardian info, and grade easily.

3️⃣ Progress Tracking

   • Teachers can record marks and remarks.

   • Percentages automatically calculated.

4️⃣ Field Control

   • Prevents editing of fee-related fields to maintain accuracy.


---

🛠 Tech Stack

• Platform: ServiceNow

• Frontend: UI Builder / Form Views

• Backend: ServiceNow Tables (u_education, u_admission, u_student_fee_details, u_student_progress)

• Automation: Business Rules, Client Scripts, UI Policies


---

🏆 Contributions

• Designed ServiceNow tables and relationships for Education, Admission, Fee, and Progress modules.

• Implemented Business Rules for fee auto-calculation and progress computation.

• Configured UI Policies and Client Scripts for form control and field automation.

• Created form views for student data entry and progress tracking.


---

📜 License

• This project was developed for educational purposes to demonstrate ServiceNow application development and workflow automation.
