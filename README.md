## Student Information Management - UI Design & Documentation


*Live Demo: [nsbm-erp.vercel.app](https://nsbm-erp.vercel.app)*

The Student Registration System is the backbone of university enrollment management. It handles 
admission applications, profile creation, document verification, and course registration. By automating fee 
calculation, payment collection, and timetable generation.
---

## 🌟 Live Demo

**Experience the full system live:**  
[https://nsbm-erp.vercel.app](https://nsbm-erp.vercel.app)  

> *Login Page Preview from your document:*  
> **"Welcome to NSBM ERP — Login to access your portal."**

---

## Business Processes

*High-Level Business Processes for the Entire ERP System*

1. New student admission.  
•  Collect student applications, Verify documents, If documents valid proceed to enrollment, 
If invalid request resubmission.  
2. Document verification & eligibility check.  
•  Check academic certificates, If eligible approve registration, If not eligible reject 
application with feedback.  
3. Student profile creation & ID generation.  
•  Input student personal details, Assign student ID, Upload photo, Confirm profile creation.  
4. Course registration & subject selection.  
•  Display available courses, Students select courses, Check prerequisites, If prerequisites 
met register student, If not met show error & suggest alternative.  
5. Prerequisite course validation.  
•  Match students completed courses with course requirements, If validated approve 
enrollment, If fail notify students.  
6. Student ID Generation & Authentication.  
•  Generate student ID,Encode access permissions, If successful send ID to student, If fail 
retry or escalate.  
7. Fee calculation & payment processing.  
•  Calculate courses and other fees, Present payment options, If payment is successful 
generate receipt, If payment fails notify students & retry.  
8. Receipt Generation & Payment Records.  
•  Generate official receipt, Save record in ERP, Notify students.  
9. Scholarship & Financial Aid Processing.  
•  Receive application, Verify eligibility, If approved apply scholarship to fee, If rejected 
notify student.  
10. Hostel/Transport Allocation.   
•  Student applies for hostel/transport, Check availability, If available allocate, If full add to 
waiting list.  
11. Timetable & Class Schedule Generation.   
•  Check course enrollment, Allocate class slots, Generate timetable, Notify students.  
12. Attendance Tracking & Reporting.  
•  Record daily attendance, Generate weekly/monthly reports, Notify students with low 
attendance.  
13. Exams & Results.  
•  Register students for exams, Schedule exam timetable, Faculty enters results, Validate 
results, If valid publish results to student portal, If invalid request corrections.  
14. Transcript Generation.  
•  Compile validated results, Generate transcript, If complete issue to students, If 
incomplete hold until pending results are available.  
15. Student Status Updates.  
•  Check academic progress, Update status, Notify students.  
16. Academic Progress Tracking & Reporting.  
•  Monitor semester results, Generate progress report, If behind alert academic advisor, If 
on track continue normal tracking.  
17. Semester Fee Payment.  
•  Generate semester fee bill, Present payment methods, If payment successful Update 
financial record & issue receipt, If payment fails notify students & allow retry, If not paid 
before deadline apply late fee penalty.  
18. Communication & Notifications.  
•  Send alerts via outlook.  
19. Alumni Record Management.  
•  Graduate student, Verify completion, Move record to alumni database. 
20. Student Feedback & Grievance Handling.  
•  Collect student feedback through portal, Categorize feedback or complaint, Assign to the 
department responsible.

*Sub-Processes (Step-by-Step Workflow)*

1. Submit admission application → Upload required documents  
2. Verify eligibility → (if approved, continue; if rejected, notify student)  
3. Create student profile → Generate student ID  
4. Course selection → Prerequisite validation  
5. Calculate tuition fees → Payment processing → Generate receipt  
6. Timetable generation → Notification to student  
7. Exam registration → Transcript/records update 

---
## 🖼️ Figma Designs

Each module of the system is designed in Figma. Explore the UI prototypes below:

- 🎨 **Main Project:** [NSBM ERP - Full Design](https://www.figma.com/design/Sr5XxbNgxNKynJEB6fD61U/NSBM-ERP?node-id=30-1765&t=lbmxtx5HzdxgTfMo-1)
- 👨‍🎓 **Student Portal:** [View Design](https://www.figma.com/proto/Sr5XxbNgxNKynJEB6fD61U/NSBM-ERP?node-id=18-1519&p=f&t=VXU2Hd3kNRJKpmZY-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=18%3A1519&show-proto-sidebar=1)
- 🧑‍💼 **Admin Portal:** [View Design](https://www.figma.com/proto/Sr5XxbNgxNKynJEB6fD61U/NSBM-ERP?node-id=24-189&p=f&t=OvyJHdGs4yz8rM6O-1&scaling=min-zoom&content-scaling=fixed&page-id=1%3A163&starting-point-node-id=24%3A189&show-proto-sidebar=1)
- 🧾 **Registrar Module:** [View Design](https://www.figma.com/proto/Sr5XxbNgxNKynJEB6fD61U/NSBM-ERP?node-id=28-1367&p=f&t=DxX5iv6gdKYkVrfd-1&scaling=min-zoom&content-scaling=fixed&page-id=28%3A1363&starting-point-node-id=28%3A1367&show-proto-sidebar=1)
- 💰 **Finance Module:** [View Design](https://www.figma.com/proto/Sr5XxbNgxNKynJEB6fD61U/NSBM-ERP?node-id=30-1767&p=f&t=FWr0HCuPatmHKFBQ-1&scaling=min-zoom&content-scaling=fixed&page-id=30%3A1765&starting-point-node-id=30%3A1767&show-proto-sidebar=1)

---

## 🚀 Features

### 👨‍🎓 Student Module
- View enrolled courses, results, and payments  
- Manage student profile and ID card  
- Check attendance and exam schedules  

### 🧑‍💼 Admin Module
- Manage users, admissions, and verifications  
- Generate analytical and admission reports  
- Dashboard for overall system overview  

### 🧾 Registrar Module
- Manage attendance, exam schedules, and timetables  
- Allocate subjects and departments  
- Monitor student academic progress  

### 💰 Finance Module
- Generate invoices and manage scholarships  
- Track payments and balances  
- Produce financial reports  

---

## Team Members

  BAIP Priyadarshani – 32388  
  KAMM Kanangama – 32261  
  LMO Piyumika – 32754  
  KDS De Silva – 32485  
  EGJWD Egodage – 32385  
  MWVL Rupasingha – 32400  
  CDB Samarakoon – 33048  
  BP Fernando – 32924  
  RMSP Ranathunga – 32328  
  CA Ediriweera – 32521  
  JAC Jayasinghe – 33092  

---
## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/NSBM-ERP.git
   cd NSBM-ERP

2. **Open directly in browser**
   ```bash
   open "NSBM ERP/index.html"
   
3.**Or use a local server:**
    ```bash
    npx serve "NSBM ERP"
    
