# Clinic Appointment & Diagnostics ERD

## Overview

This project presents an **Entity Relationship Diagram (ERD)** for a clinic system that manages **patients, doctors, appointments, consultations, diagnostic tests, reports, and payments**.

---

## Key Features

- Handles **appointment → consultation → diagnostics → reports flow**
- Supports multiple **doctors and specializations**
- Tracks **patient visits and history**
- Allows **multiple tests per consultation**
- Stores **reports linked to prescribed tests**
- Flexible **payment system** (appointment or consultation)

---

## Main Entities

- Patients
- Doctors
- Specializations
- Appointments
- Consultations
- Diagnostic Tests
- Prescribed Tests
- Test Reports
- Payments

---

## Relationships

- Patient → Appointments (1:N)
- Doctor → Appointments (1:N)
- Appointment → Consultation (1:1)
- Consultation → Tests (1:N)
- Test → Reports (1:1)
- Patient → Payments (1:N)

---
