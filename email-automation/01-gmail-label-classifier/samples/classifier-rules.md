## 🧠 Gmail Classifier Rules

This file documents the classification rules used in the n8n Text Classifier node.

The classifier reads email details and chooses exactly one label from the predefined Gmail labels.

## 📌 Base Instruction

You are an email classifier.

Read the email subject and body, then choose exactly ONE label from the predefined Gmail labels.

Do not create new labels.

## Decision Rules

---

### Bills & Utilities

### 🔑 Keywords: Bills & Utilities

- bill
- due
- payment
- statement
- invoice
- Cox
- AT&T
- utility
- grocery
- Walmart
- pickup
- delivery
- receipt
- food order

Choose this label when the email is mainly about bills, utilities, invoices, rent, receipts, or payment statements.

---

### Alerts & Newsletters


Choose this label when the email is an automated alert, newsletter, promotion, marketing email, or general subscription update with no direct action required.

---

### Shipping & Orders

### 🔑 Keywords: Shipping & Orders

- tracking
- shipped
- delivered
- package
- FedEx
- UPS
- USPS
- order
- purchase
- confirmation
- Ulta
- Amazon
- Target
- Walmart
- shipment

Choose this label when the email is mainly about an online order, purchase confirmation, package tracking, shipment, or delivery update.

---

### Learning & Courses

### 🔑 Keywords: Learning & Courses

- course
- lesson
- training
- certificate
- Coursera
- Udemy
- OpenAI Academy

Choose this label when the email is related to courses, training, certificates, lessons, or learning platforms.

---

### High Priority

### 🔑 Keywords: High Priority

- Account suspended
- Failed payment
- Payment overdue
- Invoice unpaid
- Verify your identity
- Confirm your account
- Password reset
- Legal notice
- Medical appointment
- Service interruption
- Access blocked
- Account locked
- Delivery failed
- Refund declined

Choose this label when the email requires urgent attention, includes a deadline, warns about a consequence, reports a failed payment, mentions account suspension, account lock, service interruption, legal notice, medical notice, or delivery failure.

---

### Job Alerts

### 🔑 Keywords: Job Alerts

- job alert
- jobs
- opening
- hiring
- recruiter
- application
- interview
- role
- career
- LinkedIn
- Indeed
- Dice
- Glassdoor
- Workday


Choose this label when the email is about job openings, recruiter messages, interview updates, application status, or career platform alerts.

---












