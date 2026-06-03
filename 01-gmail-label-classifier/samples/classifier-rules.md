🧠 Gmail Classifier Rules

This file documents the classification rules used in the n8n Text Classifier node.

The classifier reads email details and chooses exactly one label from the predefined Gmail labels.

## 📌 Base Instruction

You are an email classifier.

Read the email details and choose exactly ONE label that best fits the email.

Use only the labels listed below. Do not create new labels.

---

## 💡 Label: Bills & Utilities

Emails about monthly bills, internet, phone, electricity, water, gas, rent, payment due notices, weekly orders, and receipts.

### 🔑 Keywords

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

---

## 📰 Label: Alerts & Newsletters

Automated alerts, security notifications, promotional newsletters, marketing emails, and subscription digests.

Use this label only if no direct personal action is required from the user.

---

## 📦 Label: Shipping & Orders

Emails about online purchases, order confirmations, retail stores, beauty products, clothes, electronics, household items, package tracking, delivery updates, FedEx, UPS, USPS, or shipment status.

### 🔑 Keywords

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

---

## 🎓 Label: Learning & Courses

Emails about courses, training, certificates, Coursera, Udemy, OpenAI Academy, or learning platforms.

### 🔑 Keywords

- course
- lesson
- training
- certificate
- Coursera
- Udemy
- OpenAI Academy

---

## 🚨 Label: High Priority

Emails from a real company or person directly addressed to the user that require immediate action.

Includes emails about:

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

The email must demand a specific action from the user within a deadline or include a consequence if no action is taken.

---

## 💼 Label: Job Alerts

Emails about job openings, LinkedIn jobs, Indeed, Dice, recruiter alerts, company career alerts, interview updates, or application status.

### 🔑 Keywords

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