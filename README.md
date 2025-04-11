
# Health Care Management System
A full-stack web application designed to streamline the process of connecting patients with specialized doctors, managing appointments, and maintaining digital records.

## Overview
This system allows patients to input their symptoms and view a list of doctors who specialize in treating the relevant conditions. Patients can view doctor profiles, check available time slots, and request appointments. Doctors can then accept or reject these requests. Upon completion of the consultation, doctors can upload a prescription, and patients are allowed to rate and review their experience.

## Key Features
- Symptom-based doctor recommendations
- Doctor profile viewing and schedule management
- Appointment request and confirmation system
- Notification system for appointment status updates
- Prescription upload and storage
- Post-consultation feedback and rating functionality

## Tech Stack
- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MySQL

## Functionality

### Patient Module
- Register and log in
- Enter symptoms to get recommended doctors
- View doctor profiles and availability
- Book appointments by selecting available time slots
- Receive notifications on appointment status
- View prescriptions and give feedback after appointments

### Doctor Module
- Log in to access personal dashboard
- Receive and manage appointment requests
- Accept or reject appointment requests
- Upload prescriptions post-consultation
- View patient ratings and feedback

## Getting Started
### Prerequisites

- Node.js and npm
- MySQL Server

### Installation
#### Backend

```bash
cd backend
npm install
```

Configure the `.env` file with your MySQL database credentials.

```bash
npm start
```

#### Frontend

```bash
cd frontend
npm install
npm start
```

## Folder Structure

```
project-root/
│
├── backend/            # Node.js & Express backend
├── frontend/           # React frontend
├── README.md
```

## Contact

For questions or collaboration inquiries, please contact:

**Tayyba**  
Email: tayybahaider198@gmail.com  
GitHub: [Tayyba80](https://github.com/Tayyba80)
```
