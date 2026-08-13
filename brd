# 🎓 Utama Insani Integrated Education System

<p align="center">
  <b>Integrated Education ERP • SIAKAD • LMS • Admission • Finance • HR • CRM</b><br>
  Untuk Ekosistem Pendidikan Yayasan Utama Insani Panongan
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Planning-blue" alt="Status Planning">
  <img src="https://img.shields.io/badge/Architecture-Multi%20School-orange" alt="Multi School">
  <img src="https://img.shields.io/badge/Payment-Midtrans-success" alt="Midtrans">
  <img src="https://img.shields.io/badge/Scope-TK%20%7C%20SD%20%7C%20SMP%20%7C%20SMK-red" alt="Scope">
</p>

---

# 📌 Overview

**Utama Insani Integrated Education System** adalah rancangan platform pendidikan terpadu untuk mengelola seluruh proses operasional, akademik, pembelajaran, administrasi, keuangan, SDM, penerimaan siswa, dan marketing pada seluruh satuan pendidikan di bawah Yayasan Utama Insani Panongan.

Sistem ini dirancang bukan sekadar sebagai **SIAKAD**, tetapi sebagai satu ekosistem digital pendidikan yang mengintegrasikan:

- Yayasan;
- TK;
- SDIT;
- SMP Islam Plus;
- SMK Kesehatan;
- PPDB/SPMB;
- CRM Marketing;
- SIAKAD;
- KRS / Study Plan;
- Kurikulum;
- Mata Pelajaran;
- Jadwal;
- Ruang;
- Presensi;
- E-Learning / LMS;
- Tugas;
- Quiz;
- Ujian;
- Nilai;
- Rapor;
- Pembayaran;
- Midtrans;
- Administrasi;
- HR;
- Guru;
- Pegawai;
- Fasilitas;
- Kegiatan;
- Dokumen;
- Alumni;
- Dashboard Management;
- Internal Student Retention.

Konsep utama:

```text
ONE FOUNDATION
      ↓
MULTI SCHOOL
      ↓
MULTI PANEL
      ↓
ONE INTEGRATED DATA ECOSYSTEM
```

---

# 🏛️ Organization Scope

Platform dirancang untuk mendukung empat satuan pendidikan:

| Unit | Jenjang |
|---|---|
| TK Utama Insani | TK |
| SDIT Utama Insani | SD |
| SMP Islam Plus Utama Insani | SMP |
| SMKS Kesehatan Utama Insani | SMK |

Tujuan utamanya adalah membangun satu alur pendidikan terpadu:

```text
TK
 ↓
SDIT
 ↓
SMP Islam Plus
 ↓
SMK Kesehatan
```

Data siswa tidak perlu dibuat ulang setiap berpindah jenjang.

Satu siswa akan memiliki satu identitas utama, sedangkan riwayat sekolah disimpan sebagai **Enrollment History**.

---

# 🎯 Business Vision

Membangun satu platform digital Yayasan Utama Insani yang mengintegrasikan:

```text
Marketing
    ↓
Admission
    ↓
Enrollment
    ↓
Academic
    ↓
Learning
    ↓
Assessment
    ↓
Finance
    ↓
Graduation
    ↓
Retention
    ↓
Alumni
```

Sistem diharapkan menjadi **Single Source of Truth** untuk seluruh data pendidikan yayasan.

---

# 🚀 Business Objectives

## 1. Centralized Education Data

Menyediakan satu sumber data utama untuk seluruh unit sekolah.

## 2. Digital Student Journey

Mendigitalisasi perjalanan siswa:

```text
Prospect
   ↓
Applicant
   ↓
Accepted
   ↓
Student
   ↓
Graduate
   ↓
Alumni
```

## 3. Internal Education Continuity

Meningkatkan conversion siswa internal:

```text
TK → SD
SD → SMP
SMP → SMK
```

## 4. Integrated Academic Management

Mengelola secara terpadu:

- tahun akademik;
- semester;
- kurikulum;
- kelas;
- rombel;
- ruang;
- mata pelajaran;
- KRS;
- guru;
- jadwal;
- presensi;
- ujian;
- nilai;
- rapor.

## 5. Integrated Learning

Menggabungkan SIAKAD dan LMS sehingga kelas pembelajaran tidak perlu dibuat manual.

## 6. Integrated Finance

Mengelola tagihan, pembayaran, invoice, discount, beasiswa, cicilan, outstanding, dan rekonsiliasi.

Midtrans digunakan sebagai payment gateway.

## 7. Integrated Human Resource

Mengelola data guru dan pegawai secara terpusat.

## 8. Management Visibility

Memberikan dashboard terintegrasi kepada Yayasan dan kepala unit.

---

# 🧭 Design Principles

## Centralized but Segmented

Semua data berada dalam satu ekosistem, tetapi akses dibatasi berdasarkan unit sekolah.

## Multi-School

Satu platform mendukung:

```text
Foundation
├── TK
├── SD
├── SMP
└── SMK
```

## Role-Based Access Control

Setiap pengguna hanya memiliki akses sesuai peran.

## Configurable

TK, SD, SMP, dan SMK memiliki proses akademik yang berbeda.

## Parent-Centric

Satu akun orang tua dapat terhubung ke beberapa anak.

## Student Lifecycle

Riwayat siswa tetap terhubung sepanjang berada dalam ekosistem Yayasan.

---

# 🏗️ High-Level Architecture

```text
                    YAYASAN UTAMA INSANI
                              │
                              ▼
                     FOUNDATION PANEL
                              │
          ┌───────────────────┼────────────────────┐
          │                   │                    │
          ▼                   ▼                    ▼
      ACADEMIC            FINANCE                HR
          │                   │                    │
          └───────────────────┼────────────────────┘
                              │
                              ▼
                      MASTER DATA LAYER
                              │
         ┌────────────────────┼────────────────────┐
         │                    │                    │
         ▼                    ▼                    ▼
        TK                   SD                  SMP
                                                   │
                                                   ▼
                                                  SMK
```

---

# 🧱 Multi-Tenant / Multi-School Model

Setiap transaksi harus memiliki context minimal:

```text
foundation_id
school_unit_id
academic_year_id
semester_id
user_id
role_id
```

Contoh:

```text
Yayasan Utama Insani
│
├── Unit 01 — TK
├── Unit 02 — SD
├── Unit 03 — SMP
└── Unit 04 — SMK
```

---

# 👥 User Panels

## 1. Foundation Management Panel

Digunakan oleh:

- Pengurus Yayasan;
- Pimpinan;
- Super Admin;
- Executive Management.

Fitur:

- consolidated dashboard;
- statistik seluruh unit;
- finance overview;
- PPDB;
- HR;
- academic overview;
- marketing;
- internal continuation;
- audit;
- reporting.

## 2. School Management Panel

Digunakan oleh:

- Kepala Sekolah;
- Wakil Kepala Sekolah;
- Tata Usaha;
- Operator.

Fitur:

- student management;
- teacher management;
- academic;
- class;
- schedule;
- room;
- activities;
- reports.

## 3. Academic Panel

Digunakan oleh:

- Wakasek Kurikulum;
- Admin Akademik;
- Wali Kelas;
- Koordinator Program.

Fitur:

```text
Academic Year
Semester
Curriculum
Class
Room
Subject
Teacher Assignment
KRS
Schedule
Exam
Grade
Report Card
```

## 4. Teacher Panel

```text
Dashboard
My Schedule
My Classes
My Subjects
Learning Materials
Assignments
Quiz
Examinations
Attendance
Student Scores
Grade Book
Calendar
Announcements
Messages
Teaching History
```

## 5. Student Panel

```text
Profile
Academic
My Class
My Subjects
My KRS
Schedule
Learning
Assignments
Exams
Attendance
Grades
Report Card
Activities
Announcements
Payments
Documents
Notifications
```

## 6. Parent Panel

```text
Parent Account
│
├── Anak 1 — TK
├── Anak 2 — SD
└── Anak 3 — SMP
```

Parent dapat:

- switch anak;
- melihat nilai;
- melihat kehadiran;
- melihat tugas;
- melihat jadwal;
- melihat ujian;
- melihat tagihan;
- melakukan pembayaran;
- mengunduh receipt;
- melihat kegiatan;
- menerima informasi jenjang berikutnya.

## 7. Finance Panel

```text
Finance Dashboard
Fee Master
Billing Rules
Student Billing
Invoices
Payments
Midtrans Transactions
Settlement
Reconciliation
Discount
Scholarship
Installment
Refund
Outstanding
Reports
```

## 8. Marketing & Admission Panel

```text
Lead Management
Prospect
Campaign
Follow-up
Applicant
Admission
Test
Interview
Selection
Registration
Enrollment
Internal Continuation
Analytics
```

## 9. HR Panel

```text
Employee
Teacher
Position
Organization
Contract
School Assignment
Teacher Workload
Attendance
Leave
Permission
Performance
Document
Training
Certification
Payroll
History
```

---

# 🗃️ Master Data

```text
Foundation
School Unit
School Level
Academic Year
Semester
Curriculum
Department
Program
Major
Class
Room
Subject
Student
Parent
Guardian
Employee
Teacher
Fee Type
Activity
Document Type
Role
Permission
```

---

# 🧑‍🎓 Unified Person & Student Record

Sistem harus memiliki konsep **Unified Person Record**.

```text
Person ID:
P-000124

Student History:
2026 — TK Utama Insani
2032 — SDIT Utama Insani
2038 — SMP Islam Plus
2041 — SMK Kesehatan
```

Saat berpindah jenjang:

```text
New Enrollment
```

bukan:

```text
New Person
```

---

# 📝 PPDB / SPMB Module

```text
Lead
 ↓
Create Account
 ↓
Application Form
 ↓
Document Upload
 ↓
Registration Fee
 ↓
Verification
 ↓
Admission Test
 ↓
Interview
 ↓
Selection
 ↓
Accepted / Rejected
 ↓
Re-registration
 ↓
Initial Payment
 ↓
Student Creation
 ↓
Class Placement
 ↓
ACTIVE STUDENT
```

---

# 📄 PPDB Data

```text
Student Name
Birth Place
Birth Date
Gender
Address
Previous School
Parent
Guardian
Phone
Email
School Selection
Program Selection
Academic Year
```

---

# 📂 PPDB Document Management

```text
Kartu Keluarga
Akta Kelahiran
NISN
KTP Orang Tua
Pas Foto
Ijazah
Rapor
Dokumen Pendukung
```

Dokumen sensitif harus private.

---

# 📈 Marketing CRM

```text
lead_id
student_name
parent_name
phone
email
interested_school
source
campaign
current_school
followup_status
marketing_owner
interest_level
last_contact
next_followup
notes
```

---

# 📣 Marketing Sources

```text
Instagram
Website
WhatsApp
Google
Referral
Alumni
Current Student
Event
Open House
Banner
Flyer
School Visit
Internal Yayasan
Other
```

---

# 🔁 Internal Continuation Funnel

```text
TK B
 ↓
Potential SD Candidate

SD Grade 6
 ↓
Potential SMP Candidate

SMP Grade 9
 ↓
Potential SMK Candidate
```

---

# 🧲 Continuation Status

```text
Not Contacted
Contacted
Interested
Need Follow-Up
Not Interested
Applied
Accepted
Registered
Converted
```

---

# 📊 Marketing Dashboard

```text
Total Leads
New Leads
Contacted
Qualified
Applicant
Accepted
Registered
Conversion Rate
Lead Source Performance
Campaign Performance
Marketing Staff Performance
Internal Conversion Rate
External Conversion Rate
```

---

# 📚 SIAKAD Module

```text
Academic Year
Semester
Curriculum
Grade
Program
Class
Rombel
Student
Teacher
Subject
Room
KRS
Schedule
Attendance
Exam
Grade
Report Card
Promotion
Graduation
```

---

# 📅 Academic Year

```text
2026/2027
├── Semester Ganjil
└── Semester Genap
```

Status:

```text
Planning
Active
Grade Submission
Closed
Archived
```

---

# 📘 Curriculum Management

```text
TK Curriculum
SD Curriculum
SMP Curriculum
SMK Curriculum
```

Untuk SMK:

```text
SMK Kesehatan
├── Keperawatan
└── Farmasi
```

---

# 📖 Subject Management

```text
subject_code
subject_name
school_unit
education_level
grade
curriculum
category
teacher
credit_or_hour
minimum_criteria
description
learning_outcomes
active_status
```

---

# 🗂️ KRS / Study Plan

TK / SD / SMP:

```text
Package Curriculum
```

SMK:

```text
Structured Study Plan
```

atau KRS.

---

# 🔄 KRS Workflow

```text
Academic Opens KRS
        ↓
System Generates Default Subjects
        ↓
Student Reviews
        ↓
Optional Subject Selection
        ↓
Submit
        ↓
Homeroom / Academic Approval
        ↓
KRS Active
```

---

# 🏫 Classroom Management

```text
class_id
class_name
grade
homeroom_teacher
capacity
academic_year
room
school_unit
students
```

---

# 🚪 Room Management

```text
room_code
room_name
building
floor
capacity
room_type
facility
availability
school_unit
```

Jenis ruang:

```text
Classroom
Laboratory
Computer Lab
Nursing Lab
Pharmacy Lab
Meeting Room
Hall
Other
```

---

# ⚠️ Schedule Conflict Detection

Sistem harus mencegah:

- guru mengajar dua kelas pada waktu sama;
- satu ruangan digunakan dua kegiatan pada waktu sama;
- jadwal siswa bertabrakan;
- jadwal ujian bertabrakan.

---

# 🕒 Schedule Management

```text
school_unit
academic_year
semester
class
subject
teacher
room
day
start_time
end_time
```

---

# ✅ Student Attendance

```text
Present
Sick
Permission
Absent
Late
School Activity
```

---

# 💻 E-Learning / LMS

Ketika assignment akademik sudah dibuat:

```text
Teacher
+
Subject
+
Class
+
Semester
```

sistem otomatis membuat:

```text
Learning Course
```

---

# 📦 Course Structure

```text
Course
│
├── Overview
├── Learning Outcomes
├── Modules
│   ├── Week 1
│   ├── Week 2
│   ├── Week 3
│   └── ...
├── Materials
├── Assignments
├── Quiz
├── Discussion
├── Attendance
├── Examination
└── Grade
```

---

# 📚 Learning Materials

```text
Text
PDF
PowerPoint
Document
Image
Video Link
External Link
Downloadable File
Worksheet
```

---

# 📝 Assignment Management

```text
assignment_title
description
class
subject
start_date
due_date
attachment
submission_type
maximum_score
late_submission_rule
```

Submission:

```text
student
submission_date
file
comment
status
score
teacher_feedback
```

---

# 📊 Learning Progress

```text
Material Completed
Assignment Submitted
Quiz Completed
Exam Completed
Attendance
Current Grade
```

---

# 🧪 Examination System

```text
Quiz
Daily Test
Assignment Test
Mid Semester
Final Semester
Practical Examination
Competency Examination
Remedial
Other
```

---

# 🧠 Question Bank

```text
subject
topic
competency
difficulty
question_type
question
answer
score
explanation
```

---

# ❓ Question Types

```text
Multiple Choice
Multiple Answer
True / False
Short Answer
Essay
Matching
File Submission
```

---

# 🔐 Exam Security

- authenticated access;
- exam schedule;
- start/end time;
- exam token;
- random question;
- random answer;
- question pool;
- time limit;
- one active attempt;
- autosave;
- activity log;
- session monitoring;
- IP logging;
- audit trail.

---

# 🔄 Exam Workflow

```text
Teacher Creates Question
        ↓
Question Bank
        ↓
Exam Created
        ↓
Review / Approval
        ↓
Exam Published
        ↓
Student Login
        ↓
Exam
        ↓
Submit
        ↓
Auto / Manual Grading
        ↓
Teacher Review
        ↓
Grade Book
```

---

# 📊 Grade Management

```text
Assignments
Quiz
Attendance
Mid Exam
Final Exam
Practical
Project
Teacher Assessment
```

Contoh formula:

```text
Assignment  20%
Quiz        10%
Mid Exam    25%
Final Exam  30%
Practical   15%
```

---

# 🔒 Grade Workflow

```text
Teacher Input
     ↓
Draft
     ↓
Teacher Submit
     ↓
Academic Review
     ↓
Approved
     ↓
Locked
     ↓
Report Card
```

Perubahan setelah lock:

```text
Change Request
Reason
Old Value
New Value
Approver
Timestamp
```

---

# 📜 Report Card

- mata pelajaran;
- nilai;
- predikat;
- deskripsi;
- presensi;
- kegiatan;
- ekstrakurikuler;
- catatan wali kelas;
- perkembangan siswa.

---

# 💰 Finance Management

Midtrans hanya berfungsi sebagai payment gateway.

```text
Finance System
     ↓
Invoice
     ↓
Midtrans
     ↓
Payment
     ↓
Webhook
     ↓
Finance Ledger
```

---

# 🧾 Fee Master

```text
Registration Fee
Admission Fee
Development Fee
Monthly Tuition / SPP
Semester Fee
Laboratory Fee
Practical Fee
Exam Fee
Activity Fee
Uniform
Book
Extracurricular
Graduation
Other
```

---

# 🧮 Billing Rules

```text
school_unit
grade
academic_year
semester
student
program
fee_type
```

Dukungan:

```text
Recurring Billing
One-Time Billing
Custom Billing
Discount
Scholarship
Waiver
Installment
Adjustment
```

---

# 🧾 Student Invoice

```text
Invoice:
INV-SMK-2026-000001

Student:
Example Student

Items:
SPP August        Rp500.000
Laboratory        Rp100.000

Total             Rp600.000
Paid              Rp0
Outstanding       Rp600.000

Status:
UNPAID
```

---

# 💳 Midtrans Integration

Tahap awal:

```text
Midtrans Snap
```

Flow:

```text
Parent / Student
       ↓
Open Invoice
       ↓
Click Pay
       ↓
Backend Creates Midtrans Transaction
       ↓
Snap Token
       ↓
Midtrans Checkout
       ↓
Payment
       ↓
Midtrans
       ↓
Webhook
       ↓
Backend Verification
       ↓
Update Invoice
       ↓
Update Ledger
       ↓
Create Receipt
       ↓
Notification
```

---

# 🔢 Midtrans Order ID

```text
UI-TK-2026-INV000001
UI-SD-2026-INV000002
UI-SMP-2026-INV000003
UI-SMK-2026-INV000004
```

---

# 💵 Payment Status

```text
UNPAID
PENDING
PAID
FAILED
EXPIRED
CANCELLED
REFUNDED
PARTIAL
```

---

# 🔄 Payment Reconciliation

```text
Invoice Amount
Paid Amount
Gateway Transaction
Settlement
Payment Date
Payment Method
Student
School Unit
```

Exception:

```text
Payment received but invoice not updated
Duplicate notification
Incorrect amount
Expired payment
Refund
Manual payment
```

---

# 🧾 Payment Receipt

```text
receipt_number
invoice
student
amount
payment_date
method
transaction_id
school
status
```

---

# 📉 Outstanding Management

```text
Total Billing
Total Paid
Total Outstanding
Collection Rate
Overdue
Outstanding by Student
Outstanding by School
Monthly Revenue
Payment Method
```

---

# 👨‍🏫 Employee Management

```text
employee_id
name
gender
contact
email
position
department
employment_status
join_date
school_assignment
qualification
certification
documents
status
```

---

# 🧑‍🏫 Multi-School Teacher Assignment

```text
Teacher A

Primary:
SMP

Additional Teaching:
SMK
```

---

# 🏢 Organization Structure

```text
Foundation
│
├── Management
├── Finance
├── HR
│
├── TK
│   └── School Organization
│
├── SD
│   └── School Organization
│
├── SMP
│   └── School Organization
│
└── SMK
    └── School Organization
```

---

# 💼 Position Management

```text
Foundation Management
Principal
Vice Principal
Academic
Student Affairs
Finance
Administration
Homeroom Teacher
Teacher
Laboratory Staff
Operator
Marketing
Other
```

---

# ⏱️ Teacher Workload

```text
Teacher
Subject
Class
Weekly Hours
Additional Duty
Total Workload
```

Status:

```text
Under Allocation
Normal
Over Allocation
```

---

# 🕘 Employee Attendance

```text
Present
Late
Permission
Sick
Leave
Absent
Official Duty
```

---

# 🌴 Leave Management

```text
Employee Request
      ↓
Supervisor
      ↓
Approve / Reject
      ↓
HR
      ↓
Attendance Updated
```

---

# 💼 Payroll

Phase lanjutan.

```text
Basic Salary
Allowance
Teaching Allowance
Position Allowance
Overtime
Deduction
Attendance Deduction
Other
```

---

# 🎉 School Activity Management

```text
School Event
Academic Event
Competition
Field Trip
Industry Visit
Health Activity
Religious Activity
Parent Meeting
Exam
Holiday
Graduation
Other
```

---

# 📅 Event Data

```text
event_name
school
organizer
start_date
end_date
location
participants
description
attachment
attendance
documentation
```

---

# 🏢 Facility Management

```text
Building
Room
Laboratory
Equipment
Computer
Projector
Nursing Equipment
Pharmacy Equipment
Furniture
Other
```

---

# 🧾 Asset Record

```text
asset_code
asset_name
category
school
room
purchase_date
condition
responsible_person
status
```

---

# 🔧 Maintenance

```text
Maintenance Request
       ↓
Review
       ↓
Assigned
       ↓
In Progress
       ↓
Completed
```

---

# 🗄️ School Administration

```text
Incoming Letter
Outgoing Letter
Student Letter
Employee Letter
Certificate
Archive
Document
Template
Numbering
Approval
```

---

# 📄 Student Letter

```text
Active Student Letter
Recommendation
Permission
Statement
Graduation Document
Other
```

---

# 🔔 Notification

```text
Academic
Finance
PPDB
Assignment
Exam
Attendance
Activity
General
Emergency
```

Channel:

```text
In-App
Email
WhatsApp — Future
Push Notification — Future
```

---

# 👪 Parent Relationship Management

```text
View Children
Switch Child
View Attendance
View Grade
View Schedule
View Assignment
View Exam
View Billing
Pay Invoice
Download Receipt
View Activities
Receive Announcement
Internal Re-registration
```

---

# 🎓 Graduation & Alumni

```text
Active Student
      ↓
Graduation Verification
      ↓
Graduated
      ↓
Alumni
```

---

# 👤 Alumni Data

```text
alumni_id
student_history
graduation_year
school
program
contact
further_education
employment
consent
```

---

# 📊 Management Dashboard

## Education KPI

```text
Total Students
Students by Unit
New Students
Graduated
Attendance
Average Grade
Active Classes
Active Teachers
Teacher Ratio
```

## Finance KPI

```text
Total Billing
Collected
Outstanding
Collection Rate
Revenue by School
Outstanding by School
Payment Trend
```

## Marketing KPI

```text
Leads
Applicants
Accepted
Registered
Conversion Rate
Lead Source
Campaign Performance
TK → SD Conversion
SD → SMP Conversion
SMP → SMK Conversion
```

## LMS KPI

```text
Active Courses
Material Completion
Assignment Submission
Exam Participation
Student Engagement
Teacher Activity
```

---

# 🔐 Role-Based Access Control

```text
Foundation Super Admin
Foundation Management
Foundation Finance
Foundation HR

School Principal
School Admin
Academic
Finance
Student Affairs
Operator

Teacher
Homeroom Teacher

Marketing
PPDB

Student
Parent

Auditor
```

---

# 🔑 Permission Model

```text
VIEW
CREATE
UPDATE
DELETE
APPROVE
EXPORT
LOCK
UNLOCK
```

---

# 🛡️ Data Segregation

Akses dibatasi berdasarkan:

```text
Foundation
School
Role
Academic Assignment
Class
Subject
```

---

# 🧾 Audit Trail

```text
user
action
module
record
old_value
new_value
ip_address
timestamp
```

Critical event:

```text
Grade Change
Payment Change
Refund
Billing Adjustment
Student Data Change
Role Change
Permission Change
Exam Result Change
Delete Transaction
```

---

# 🔐 Authentication

```text
Email / Username
Password
Password Reset
Session Management
Login History
Account Lock
```

Strategic admin:

```text
MFA
```

---

# 🔒 Password Security

- secure password hashing;
- no plaintext password;
- password reset aman;
- password tidak dapat dibaca admin.

---

# 🛡️ Payment Security

Data bisnis yang disimpan:

```text
order_id
transaction_id
amount
payment_method
status
timestamp
```

---

# 🔏 Data Privacy

```text
Student Identity
Family Data
Address
Contact
Academic Data
Finance Data
Student Documents
Employee Data
```

Prinsip:

```text
Need to Know
+
Least Privilege
```

---

# 📂 Document Security

```text
Authentication
+
Authorization
+
Access Logging
```

---

# 💾 Backup Strategy

```text
Daily Database Backup
Periodic File Backup
Off-Site Backup
Backup Encryption
Restore Testing
```

---

# 🚨 Business Continuity

```text
Application Failure
Database Failure
Payment Gateway Failure
Internet Failure
Backup Restore
Security Incident
```

---

# 📊 Reports

Filter:

```text
Foundation
School
Academic Year
Semester
Grade
Class
Student
Teacher
Date
```

---

# 📚 Academic Reports

```text
Student List
Class List
Attendance
Teacher Assignment
Schedule
Grade
Report Card
Exam
Student Progress
Graduation
```

---

# 💰 Finance Reports

```text
Billing
Payment
Outstanding
Collection
Payment Method
Revenue
Discount
Scholarship
Refund
Reconciliation
```

---

# 📈 Marketing Reports

```text
Lead
Campaign
Source
Follow-up
Application
Enrollment
Conversion
Internal Conversion
```

---

# 👨‍💼 HR Reports

```text
Employee
Teacher
Attendance
Leave
Workload
Assignment
Contract
```

---

# 📤 Export

```text
Excel
PDF
CSV
```

---

# 🔎 Global Search

```text
Student
Parent
Employee
Invoice
Class
Subject
Document
```

---

# 🧑‍🎓 Student 360° View

```text
                 STUDENT
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
   Academic      Finance      Attendance
       │            │            │
       ├────────────┼────────────┤
       ▼            ▼            ▼
   Learning       Exam       Activities
                    │
                    ▼
              Student History
```

---

# 🔄 Cross-School Student History

```text
Student ID: UII-000123

2023–2024
TK Utama Insani

2025–2030
SDIT Utama Insani

2031–2033
SMP Islam Plus Utama Insani

2034–2036
SMK Kesehatan Utama Insani
Farmasi
```

---

# 📏 Key Business Rules

## Student Transition

```text
New Enrollment
```

bukan:

```text
New Student Person
```

## Finance Separation

Setiap transaksi wajib memiliki:

```text
school_unit_id
```

## Grade Lock

```text
Change Request
Reason
Approval
Audit
```

## Exam Access

```text
Active Student
AND
Assigned to Class/Course
AND
Exam Active
AND
Within Exam Schedule
```

## Payment Confirmation

Backend wajib memverifikasi status transaksi.

---

# ⚙️ Non-Functional Requirements

## Performance

```text
Normal Page Response < 3 seconds
Search < 3 seconds
Standard Transaction < 5 seconds
```

## Scalability

Mendukung pertumbuhan siswa, guru, kelas, program, dan unit sekolah.

## Responsive

```text
Desktop
Laptop
Tablet
Mobile Browser
```

## Availability

Baseline:

```text
>= 99.5%
```

## Accessibility

- mudah dibaca;
- kontras memadai;
- label jelas;
- mobile-friendly;
- error message jelas.

---

# 📡 Logging & Monitoring

```text
Application Error
Authentication
Payment
Background Job
Notification
Security Event
Integration Error
```

---

# 🧩 Complete Module Map

```text
01  Foundation Management
02  School Management
03  PPDB / Admission
04  Marketing CRM
05  Student Management
06  Parent Management
07  Academic / SIAKAD
08  Curriculum
09  KRS
10  Classroom
11  Scheduling
12  Room Management
13  Attendance
14  LMS
15  Assignment
16  Examination
17  Grade
18  Report Card
19  Finance
20  Midtrans
21  HR
22  Teacher Management
23  Employee Attendance
24  Payroll
25  Activities
26  Facility
27  Asset
28  Administration
29  Document
30  Notification
31  Alumni
32  Reporting
33  Dashboard
34  Audit & Security
```

---

# 🔗 System Relationship

```text
PPDB
  │
  ▼
STUDENT
  │
  ├──────────────► FINANCE
  │                   │
  │                   ▼
  │                MIDTRANS
  │
  ▼
SIAKAD
  │
  ├────► KRS
  ├────► CLASS
  ├────► SCHEDULE
  ├────► ATTENDANCE
  │
  ▼
LMS
  │
  ├────► MATERIAL
  ├────► ASSIGNMENT
  └────► EXAM
             │
             ▼
           GRADE
             │
             ▼
         REPORT CARD
```

---

# 📈 Marketing Relationship

```text
MARKETING
    │
    ▼
LEAD
    │
    ▼
PPDB
    │
    ▼
STUDENT
    │
    ▼
EDUCATION
    │
    ▼
FINAL GRADE
    │
    ▼
INTERNAL CONTINUATION
    │
    ├── TK → SD
    ├── SD → SMP
    └── SMP → SMK
```

---

# 📊 Key KPI

## PPDB

```text
Lead to Application Rate
Application to Accepted Rate
Accepted to Registration Rate
Cost per Lead
Source Conversion Rate
```

## Retention

```text
TK → SD Conversion
SD → SMP Conversion
SMP → SMK Conversion
Annual Student Retention
```

## Finance

```text
Collection Rate
Outstanding Rate
Average Payment Delay
Payment Gateway Success Rate
```

## Academic

```text
Attendance Rate
Grade Completion
Exam Participation
Student Performance
```

## LMS

```text
Course Activity
Assignment Submission
Material Completion
Teacher Activity
```

## HR

```text
Teacher Attendance
Teaching Workload
Employee Attendance
```

---

# 🚀 Development Roadmap

## Phase 0 — Foundation

```text
Authentication
RBAC
Foundation
School Unit
Master Data
Unified Person
Student
Parent
Employee
Academic Year
Audit Trail
```

## Phase 1 — Admission + SIAKAD + Finance

```text
PPDB
Marketing CRM
Student Enrollment
SIAKAD Core
Class
Subject
Teacher
Schedule
Room
Finance
Billing
Midtrans
Parent Portal
```

## Phase 2 — Digital Learning

```text
LMS
Learning Material
Assignment
Attendance
Question Bank
Exam
Grade Book
Report Card
```

## Phase 3 — School ERP

```text
HR
Employee Attendance
Leave
Payroll
Asset
Facility
Document
Administration
Activities
```

## Phase 4 — Business Intelligence

```text
Executive Analytics
Marketing Analytics
Academic Analytics
Finance Analytics
Retention Analytics
Student Risk Indicator
Forecast
```

## Phase 5 — Advanced Integration

```text
Mobile App
WhatsApp Integration
Biometric Attendance
Additional Payment Gateway
Library
Digital Signature
API Integration
Government Export/Import
SSO
Advanced BI
```

---

# 🧮 Priority Matrix

| Module | Priority |
|---|---|
| Authentication | MUST |
| RBAC | MUST |
| Master Data | MUST |
| Student | MUST |
| Parent | MUST |
| PPDB | MUST |
| SIAKAD | MUST |
| Finance | MUST |
| Midtrans | MUST |
| Class | MUST |
| Schedule | MUST |
| Room | MUST |
| Teacher | MUST |
| LMS | MUST |
| Exam | MUST |
| Grade | MUST |
| Report Card | MUST |
| Marketing CRM | MUST |
| Internal Continuation | MUST |
| HR | SHOULD |
| Asset | SHOULD |
| Document | SHOULD |
| Payroll | SHOULD |
| Mobile App | COULD |
| Biometric | COULD |
| Advanced BI | COULD |

---

# 📦 Data Migration

```text
Excel
Google Spreadsheet
Existing Website
Paper Document
Previous Application
Finance Records
Student Records
Teacher Records
```

---

# 🔄 Migration Workflow

```text
Source Identification
        ↓
Data Mapping
        ↓
Data Cleaning
        ↓
Duplicate Detection
        ↓
Validation
        ↓
Import
        ↓
Reconciliation
        ↓
Business Sign-off
```

---

# 🔍 Duplicate Detection

```text
NISN
Name
Date of Birth
Parent
Phone
Previous School
```

Duplicate tidak boleh otomatis merge apabila confidence rendah.

---

# 📋 Business Dependencies

Yayasan perlu menyediakan:

- struktur organisasi;
- daftar unit;
- role;
- user;
- kurikulum;
- mata pelajaran;
- data siswa;
- data orang tua;
- data guru;
- kelas;
- jadwal;
- ruang;
- jenis pembayaran;
- tarif;
- discount;
- beasiswa;
- aturan penilaian;
- format rapor;
- aturan KRS;
- SOP PPDB;
- SOP pembayaran;
- SOP perubahan nilai;
- SOP akademik;
- Midtrans merchant account;
- domain;
- email resmi.

---

# 💳 Midtrans Dependencies

```text
Merchant Registration
Production Activation
Payment Channel Activation
Server Key
Client Key
Notification URL
Production Domain
HTTPS
Sandbox Testing
Production Testing
Finance Reconciliation Test
```

---

# ⚠️ Project Risks

## Data Migration Risk

```text
Cleaning
Mapping
Validation
Migration Testing
```

## User Adoption Risk

```text
Simple UX
Training
User Manual
Pilot
Helpdesk
```

## Payment Risk

```text
Webhook
Transaction Verification
Retry
Reconciliation
Audit
```

## Security Risk

```text
RBAC
MFA
Encryption
Logging
Backup
Secure Development
Vulnerability Testing
```

## Exam Load Risk

```text
Load Testing
Caching
Queue
Database Optimization
Autosave
Scalable Infrastructure
```

## Scope Creep Risk

```text
Phased Development
Change Request
Backlog Management
Approval Workflow
```

---

# ✅ High-Level Acceptance Criteria

- [ ] seluruh unit sekolah dikelola dalam satu platform;
- [ ] data unit tetap tersegmentasi;
- [ ] yayasan melihat consolidated dashboard;
- [ ] PPDB berjalan sampai enrollment;
- [ ] invoice siswa dapat dibuat;
- [ ] invoice dapat dibayar via Midtrans;
- [ ] status payment ter-update otomatis;
- [ ] siswa dapat ditempatkan ke kelas;
- [ ] guru melihat assignment;
- [ ] jadwal memiliki conflict validation;
- [ ] ruang tidak dapat double-booking;
- [ ] LMS terhubung dengan SIAKAD;
- [ ] guru dapat upload materi;
- [ ] siswa dapat submit tugas;
- [ ] ujian online dapat dilakukan;
- [ ] nilai dapat diinput;
- [ ] nilai dapat di-lock;
- [ ] report card dapat dibuat;
- [ ] parent dapat melihat anak;
- [ ] parent dapat melihat tagihan;
- [ ] marketing dapat mengelola leads;
- [ ] conversion TK→SD dapat diukur;
- [ ] conversion SD→SMP dapat diukur;
- [ ] conversion SMP→SMK dapat diukur;
- [ ] audit trail tersedia;
- [ ] role dan permission bekerja;
- [ ] finance dapat melakukan reconciliation;
- [ ] student history antarjenjang tersimpan.

---

# 🏆 Definition of Success

## Operational Efficiency

Administrasi manual berkurang.

## Data Integrity

Satu data digunakan seluruh unit.

## Financial Visibility

Tagihan dan pembayaran mudah dipantau.

## Academic Visibility

Progress akademik dapat dilihat secara cepat.

## Parent Experience

Orang tua memiliki satu akses terhadap seluruh anak.

## Teacher Experience

```text
Schedule
Class
Course
Material
Assignment
Exam
Grade
Attendance
```

## Management Visibility

Yayasan memiliki dashboard keseluruhan unit.

## Marketing Growth

Marketing mempunyai funnel yang terukur.

## Internal Retention

```text
TK → SD
SD → SMP
SMP → SMK
```

---

# 🎯 Target End-State

```text
                    UTAMA INSANI 360°
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
      MARKETING         EDUCATION       MANAGEMENT
          │                │                │
          ▼                ▼                ▼
        PPDB             SIAKAD             HR
          │                │                │
          ▼                ▼                ▼
      ENROLLMENT           LMS           FACILITY
          │                │                │
          ▼                ▼                ▼
       FINANCE            EXAM          DOCUMENT
          │                │
          ▼                ▼
       MIDTRANS           GRADE
                           │
                           ▼
                       REPORT CARD
                           │
                           ▼
                       GRADUATION
                           │
                           ▼
                    INTERNAL RETENTION
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
            TK→SD        SD→SMP       SMP→SMK
```

---

# 🧭 Product Positioning

> **Integrated Education ERP, SIAKAD, LMS, Admission, Finance, HR, CRM, and School Management Platform for Yayasan Utama Insani.**

---

# 🗂️ Proposed Repository Structure

```text
utama-insani-education-system/
│
├── README.md
│
├── docs/
│   ├── BRD.md
│   ├── FRS.md
│   ├── SRS.md
│   ├── ERD.md
│   ├── API.md
│   ├── SECURITY.md
│   ├── MIDTRANS.md
│   ├── MIGRATION.md
│   └── UAT.md
│
├── apps/
│   ├── foundation-panel/
│   ├── school-panel/
│   ├── teacher-panel/
│   ├── student-panel/
│   ├── parent-panel/
│   ├── finance-panel/
│   ├── marketing-panel/
│   └── hr-panel/
│
├── backend/
│
├── database/
│   ├── migrations/
│   ├── seeders/
│   └── schemas/
│
├── services/
│   ├── payment/
│   ├── notification/
│   ├── academic/
│   └── reporting/
│
├── integrations/
│   └── midtrans/
│
├── infrastructure/
│
├── tests/
│
└── scripts/
```

---

# 🗃️ Proposed Core Entities

```text
foundations
school_units
academic_years
semesters
curriculums
programs
departments
classes
rooms
subjects

persons
students
parents
guardians
employees
teachers

enrollments
student_classes
teacher_assignments
study_plans
study_plan_items
schedules
attendances

courses
course_modules
learning_materials
assignments
assignment_submissions

question_banks
questions
exams
exam_sessions
exam_attempts
exam_answers

grade_components
grades
report_cards

fee_types
billing_rules
invoices
invoice_items
payments
payment_transactions
payment_reconciliations

leads
campaigns
lead_followups
applications
admissions
continuation_candidates

activities
facilities
assets
maintenance_requests

documents
letters
notifications

roles
permissions
user_roles
audit_logs
```

---

# 🔄 Recommended Data Lifecycle

```text
LEAD
  ↓
APPLICATION
  ↓
ADMISSION
  ↓
PERSON
  ↓
STUDENT
  ↓
ENROLLMENT
  ↓
CLASS
  ↓
SCHEDULE
  ↓
COURSE
  ↓
ASSIGNMENT / EXAM
  ↓
GRADE
  ↓
REPORT CARD
  ↓
PROMOTION
  ↓
GRADUATION
  ↓
ALUMNI
```

---

# 💳 Recommended Payment Lifecycle

```text
BILLING RULE
     ↓
INVOICE
     ↓
PAYMENT REQUEST
     ↓
MIDTRANS
     ↓
PAYMENT STATUS
     ↓
WEBHOOK
     ↓
VERIFICATION
     ↓
PAYMENT
     ↓
LEDGER
     ↓
RECEIPT
     ↓
RECONCILIATION
```

---

# 📚 Recommended Academic Lifecycle

```text
ACADEMIC YEAR
      ↓
SEMESTER
      ↓
CURRICULUM
      ↓
SUBJECT
      ↓
TEACHER ASSIGNMENT
      ↓
CLASS / KRS
      ↓
SCHEDULE
      ↓
LEARNING
      ↓
ASSESSMENT
      ↓
GRADE
      ↓
REPORT CARD
      ↓
PROMOTION
```

---

# 🧪 Recommended Exam Lifecycle

```text
QUESTION BANK
      ↓
EXAM CREATION
      ↓
PUBLISH
      ↓
EXAM SESSION
      ↓
STUDENT ATTEMPT
      ↓
AUTOSAVE
      ↓
SUBMISSION
      ↓
AUTO / MANUAL GRADING
      ↓
GRADE BOOK
      ↓
LOCK
```

---

# 📣 Recommended Marketing Lifecycle

```text
CAMPAIGN
   ↓
LEAD
   ↓
FOLLOW-UP
   ↓
INTEREST
   ↓
APPLICATION
   ↓
ACCEPTED
   ↓
REGISTERED
   ↓
STUDENT
   ↓
INTERNAL CONTINUATION
```

---

# 🔐 Recommended Security Baseline

- HTTPS only;
- password hashing;
- RBAC;
- MFA untuk strategic admin;
- secure session;
- server-side validation;
- CSRF protection;
- rate limiting;
- audit log;
- private file storage;
- signed download URL;
- encrypted backup;
- least privilege;
- database access restriction;
- secure webhook validation;
- secret management;
- vulnerability testing.

---

# 📌 Recommended Next Documents

```text
01. Business Process Document
02. Functional Requirement Specification
03. Software Requirement Specification
04. Role & Permission Matrix
05. Data Dictionary
06. ERD
07. System Architecture
08. API Specification
09. Midtrans Integration Specification
10. UI/UX Information Architecture
11. Wireframe
12. Database Design
13. Security Requirements
14. Migration Plan
15. Test Scenario
16. UAT Document
17. Deployment Architecture
18. Project Roadmap
19. Product Backlog
20. SOP Operational
```

---

# 📌 Project Status

```text
Status:
PLANNING / BUSINESS REQUIREMENT

BRD:
DRAFT

Technical Design:
NOT STARTED

Development:
NOT STARTED

Production:
NOT STARTED
```

---

# 🤝 Stakeholders

| Stakeholder | Responsibility |
|---|---|
| Yayasan | Business Owner |
| Kepala TK | Unit Stakeholder |
| Kepala SD | Unit Stakeholder |
| Kepala SMP | Unit Stakeholder |
| Kepala SMK | Unit Stakeholder |
| Academic | Academic Process Owner |
| Finance | Finance Process Owner |
| Marketing | Admission & CRM Owner |
| HR | Employee Process Owner |
| Teacher | Learning User |
| Parent | Parent Portal User |
| Student | Student Portal User |
| IT Team | Solution Owner |

---

# ⚠️ Disclaimer

Dokumen README ini merupakan rancangan awal kebutuhan bisnis dan produk.

Seluruh proses berikut masih harus divalidasi bersama stakeholder:

- kurikulum;
- KRS;
- struktur kelas;
- format rapor;
- aturan pembayaran;
- aturan beasiswa;
- aturan refund;
- SOP PPDB;
- SOP akademik;
- aturan perubahan nilai;
- struktur role;
- struktur organisasi;
- payroll;
- integrasi Midtrans;
- data migration;
- retention marketing;
- keamanan;
- compliance.

Sebelum development production dimulai, seluruh business rule kritikal harus mendapatkan persetujuan resmi.

---

# ❤️ Vision

```text
ONE FOUNDATION
ONE DATA ECOSYSTEM
MULTI SCHOOL
MULTI PANEL
INTEGRATED EDUCATION
```

**Utama Insani Integrated Education System**

> Menghubungkan Yayasan, Sekolah, Guru, Siswa, Orang Tua, Akademik, Pembelajaran, Keuangan, SDM, dan Marketing dalam satu ekosistem pendidikan terpadu.
