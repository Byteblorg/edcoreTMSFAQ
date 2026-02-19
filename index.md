# EdcoreTMS Documentation

Welcome to the official EdcoreTMS user documentation.

This portal provides guidance for administrators, trainers, and finance staff.

---

## User Manuals

- [Administrator & Teacher Manual](#table-of-contents)

---

For support, contact your system administrator.


![Version](https://img.shields.io/badge/version-1.0-blue)
![System](https://img.shields.io/badge/system-EdcoreTMS-green)
![Audience](https://img.shields.io/badge/audience-Admin%20%7C%20Teacher-orange)

---

**Document Owner:** Training Management  
**Last Updated:** 2026-02-19  
**Applies To:** EdcoreTMS Production System  

---
## Table of Contents

1. [Access and login](#access-and-login)
2. [Dashboard overview](#dashboard-overview)
3. [Creating course runs](#creating-course-runs)
4. [Funded courses requirements](#funded-courses-requirements)
5. [Managing course runs](#managing-course-runs)
6. [Adding students](#adding-students)
7. [TPG enrollment and funding](#tpg-enrollment-and-funding)
8. [Student management](#student-management)
9. [Invoices and confirmation notes](#invoices-and-confirmation-notes)
10. [Recording payments](#recording-payments)
11. [Attendance management](#attendance-management)
12. [Certification workflow](#certification-workflow)
13. [Compliance requirements](#compliance-requirements)
14. [Operational workflow summary](#operational-workflow-summary)

---

## Access and login

Navigate to: https://edcoretms.com


You will be presented with three login profiles:

- Student
- Administrator
- Teacher

Internal staff should select either:

- Administrator  
- Teacher  

Authentication methods supported:

- Username and password (issued by your manager)
- SingPass login

> ℹ️ Administrator access provides full operational control.

---

## Dashboard overview

After login, the system dashboard will be displayed.

The left sidebar contains the main modules:

- Dashboard
- Manage Course Runs
- Manage Students
- Invoicing and Finance
- Course Management

These modules allow full operational control of training workflows.

---

## Creating course runs

Course runs define the schedule and delivery of a training course.

### Navigation
Manage Course Runs → Add Run


### Required fields

| Field | Description |
|---|---|
Course | Select course from approved course list |
Start date | Course start date |
End date | Course end date |
Location | Training venue |
Trainer | Assigned trainer |
Capacity | Maximum number of participants |

Click:Save


The course run is now published to the enrollment portal.

Students may enroll immediately.

---

## Funded courses requirements

For SkillsFuture-funded courses, accuracy is critical.

Ensure the following fields are correct:

- Trainer assignment
- Course schedule
- Location
- Course configuration

EdcoreTMS automatically publishes course runs to:

- Training Partners Gateway (TPG)
- MySkillsFuture portal

> ⚠️ Incorrect course information may result in funding submission errors.

---

## Managing course runs

Navigate to:
Manage Course Runs


Select the course run.

Available actions:

- Edit course details
- Change trainer
- Change location
- Update schedule
- Update capacity
- Change course availability status

### Course availability statuses

| Status | Description |
|---|---|
Available | Open for enrollment |
Limited | Limited slots remaining |
Full | Enrollment closed |
Private | Hidden from public portal |

---

## Adding students

Students can be added using three methods.

---

### Method 1 — Enrollment portal (Recommended)

Students enroll directly through the public enrollment portal.

This ensures accurate student records.

---

### Method 2 — Manual entry

Navigate to: Manage Course Runs → Select Course Run → Add Student


Enter student details manually.

---

### Method 3 — Excel bulk import

Navigate to: Manage Course Runs → Import Students


Upload the Excel template.

This method is recommended for large batches.

---

## TPG enrollment and funding

For funded courses, students must be enrolled into Training Partners Gateway (TPG).

Required student information:

- NRIC / Identification number
- Date of birth
- Company sponsor (if applicable)

After enrollment submission, TPG returns:

- Enrollment ID
- Funding eligibility
- Accurate funding amount

> ⚠️ Without Enrollment ID, funding values are estimates only.

> ✅ Best practice: Submit TPG enrollment as early as possible.

---

## Student management

Navigate to: Manage Students


Administrators can:

- Search by student name
- Search by NRIC
- Search by batch
- View student profile
- Edit student information
- Submit enrollment to TPG

Student profile contains:

- Personal information
- Enrollment history
- Payment records
- Funding status

---

## Invoices and confirmation notes

EdcoreTMS automatically generates:

- Confirmation notes
- Invoice documents
- Payment links

Administrators must manually send confirmation notes.

### Navigation 
Student Profile → Send Confirmation Note


Confirmation notes include:

- Course details
- Schedule
- Location
- Student information
- Invoice attachment (optional)
- Payment link

### Supported payment methods

| Payment Method | Supported |
|---|---|
SkillsFuture Credit | Yes |
eNETS | Yes |
PayNow | Yes |
Bank Transfer | Yes |
Cash | Yes |
Cheque | Yes |

---

## Recording payments

Payments must be recorded in the student profile.

Navigation: Student Profile → Record Payment


Payment types include:

- Online payment
- Bank transfer
- Cash
- Cheque

> ⚠️ SSG grant disbursement will only occur after full payment is recorded.

---

## Attendance management

Navigate to: Manage Course Runs → Select Course Run


Available functions:

- View attendance sheet
- Download attendance PDF
- Download SSG QR attendance code

### Funded courses

Trainer displays QR code.

Students scan QR code to record attendance.

### Non-funded courses

Print attendance sheet.

Students sign manually.

---

## Certification workflow

After course completion:

1. Record assessment results
2. Mark pass or fail status
3. Close course run

Navigation: Course Run → Close Run

Then issue certificates: Course Run → Send Certificates


Certificates are emailed automatically.

> ℹ️ Certification is enabled only for supported courses.

---

## Compliance requirements

Training Partners Gateway deadlines:

| Requirement | Deadline |
|---|---|
Enrollment submission | Within 14 days of course start |
Assessment submission | Within 14 days of assessment |

Failure to meet deadlines may result in funding issues.

---

## Operational workflow summary

Standard operational sequence:

1. Create course run  
2. Publish course run  
3. Add students  
4. Submit TPG enrollment  
5. Send confirmation notes  
6. Record payments  
7. Conduct training  
8. Record attendance  
9. Submit assessments  
10. Close course run  
11. Issue certificates  

---

## Administrator responsibilities

Administrators are responsible for:

- Creating course runs
- Managing student enrollments
- Submitting TPG enrollments
- Sending confirmation notes
- Recording payments
- Managing attendance
- Closing course runs
- Issuing certificates

---

## Support

For assistance, contact your system administrator or manager.

---

**End of document**































## 1. Overview

EdcoreTMS is the Training Management System used to manage training operations, including:

- Course run creation and publishing
- Student enrollment and profile management
- Funding and compliance submissions (Training Partners Gateway - TPG)
- Invoice generation and payment tracking
- Attendance management
- Certification issuance

This manual provides a first-level introduction for new administrators and teachers.

---

## 2. Logging In

Access the system at:

https://edcoretms.com

You will be presented with three login profiles:

- Student
- Administrator
- Teacher

For internal staff, select either:

- **Administrator** – full operational access  
- **Teacher** – course and attendance related access  

Authentication methods:

- Username and password (issued by your manager)
- SingPass login (where enabled)

---

## 3. System Interface Overview

After login, you will see the main dashboard.

The left menu contains the primary system modules:

- Dashboard
- Manage Course Runs
- Manage Students
- Invoicing and Finance
- Course Management

These modules allow full lifecycle management of training operations.

---

## 4. Creating a Course Run

To create a course run:

1. Navigate to  
   **Manage Course Runs**

2. Click  
   **Add Run**

3. Select the course from the dropdown list

4. Enter required course details:

   - Course start date
   - Course end date
   - Location
   - Trainer
   - Class capacity
   - Course timing

5. Save the course run

Once created, the course run will be published to the enrollment portal for student registration.

---

## 5. Important: Funded Courses (SSG Funded)

For funded courses, accuracy is critical.

Ensure the following information is correct:

- Trainer details
- Course schedule
- Location
- Course information

The system will automatically submit course run data to:

- Training Partners Gateway (TPG)
- MySkillsFuture portal

This enables official enrollment and funding eligibility.

---

## 6. Managing Course Runs

Administrators can:

- Edit course details
- Change trainer
- Change location
- Update schedule
- Control course visibility

Course availability statuses include:

- Available
- Limited
- Full
- Private

---

## 7. Adding Students

Students can be added via three methods:

### Method 1: Enrollment Portal (Recommended)

Students enroll directly via the public enrollment portal.

This ensures accurate initial records.

---

### Method 2: Manual Entry

Administrators can manually add individual students into a course run.

---

### Method 3: Excel Bulk Upload

Administrators can upload multiple students using the Excel import template.

---

## 8. Mandatory Information for Funded Students

For funded courses, the following information is required:

- NRIC / Identification Number
- Date of Birth
- Sponsoring Company (if applicable)

Missing or incorrect data will result in funding calculation errors.

---

## 9. Training Partners Gateway (TPG) Enrollment

Each student must be enrolled into TPG.

Once enrolled, the system receives:

- Enrollment ID
- Accurate funding eligibility
- Correct funding amount

Without TPG enrollment, funding values shown are estimates only (80–90% accuracy).

Best Practice:  
Enroll students into TPG as early as possible.

Compliance requirements:

- Enrollment must be submitted within 14 days from course start date
- Assessment results must be submitted within 14 days from assessment date

---

## 10. Student Profile Management

Navigate to:

Manage Students

You can:

- Search by name
- Search by NRIC
- Search by batch
- View full student profile
- Edit student details
- Submit enrollment to TPG

Student profiles contain:

- Personal information
- Enrollment history
- Payment records
- Funding status

---

## 11. Invoices and Confirmation Notes

The system automatically generates:

- Confirmation notes
- Invoices
- Payment links

These include:

- Course details
- Student details
- Course schedule
- Location

Administrator must manually send the confirmation note.

To send confirmation:

1. Open student profile or batch
2. Click **Send Confirmation Note**

Optional attachments:

- Invoice PDF
- Payment links

Payment methods supported:

- eNETS
- SkillsFuture Credit
- PayNow / Red Dot payment
- Bank transfer
- Cash / Cheque

---

## 12. Recording Payments

Payments must be recorded in the student profile.

Payment methods include:

- Online payment
- Bank transfer
- Cash
- Cheque

This is critical because:

SSG grant disbursement only occurs after full payment is received and recorded.

If payment is not recorded, funding disbursement will be delayed.

---

## 13. Attendance Management

Navigate to:

Manage Course Runs → Select Batch

Options available:

- View attendance sheet (PDF)
- Download SSG QR code

For SSG-funded courses:

- Trainer displays QR code in class
- Students scan QR for attendance

For non-funded courses:

- Print attendance sheet
- Students sign manually

---

## 14. Closing Course Run and Certification

After course completion:

1. Record assessment results
2. Mark pass / fail status
3. Close the course run

Once closed, certification can be triggered.

To send certificates:

- Open batch
- Click **Send Certificate**

Note: Certification is enabled only for selected courses.

Contact your manager if certification is not available.

---

## 15. Summary of Administrator Responsibilities

Administrators are responsible for:

- Creating course runs
- Adding and managing students
- Ensuring accurate student information
- Submitting enrollments to TPG
- Sending confirmation notes
- Recording payments
- Monitoring attendance
- Closing course runs
- Triggering certifications

---

## 16. Best Practices

Always:

- Verify course details before publishing
- Enroll students into TPG early
- Record payments immediately
- Send confirmation notes only after verifying course details
- Ensure compliance deadlines are met
- Verify assessment results before closing course runs

---

## 17. Support

For assistance, contact your manager or system administrator.
Technical support is available via the Support - Open Ticket function

---

End of Level 1 User Manual
