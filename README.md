# Sulochana Care

**Sulochana Care** is an AI-powered hospital appointment and queue management system designed to simplify appointment booking through automated voice calls. It helps hospitals reduce receptionist workload while providing patients, especially elderly users, with an easy and accessible way to book appointments.

## Problem Statement

Many hospitals still rely on a single reception phone line for appointment bookings. During peak booking hours, patients often experience busy lines, long waiting times, and repeated call attempts before reaching the receptionist.

This leads to:

* Busy phone lines during appointment booking hours
* Delayed appointment scheduling
* Increased workload for reception staff
* Misuse of emergency contact numbers for regular appointments
* Poor accessibility for elderly patients who are not comfortable using websites or mobile applications

## Solution

Sulochana Care automates the appointment booking process using an AI-powered voice assistant.

When a patient calls the hospital's dedicated number:

* The system identifies returning patients using their registered phone number.
* New patients can provide their basic details through voice interaction.
* Doctor availability is verified automatically.
* A token number is generated based on the doctor's schedule.
* Appointment details are securely stored.
* The receptionist dashboard is updated in real time.
* Patients receive an appointment confirmation via SMS.

This approach reduces waiting time, eliminates busy phone lines, and provides a faster and more accessible appointment booking experience.

## Features

* AI-powered voice appointment booking
* Automated token generation
* Doctor schedule management
* Patient registration and management
* Real-time appointment queue
* Receptionist dashboard
* SMS appointment confirmation
* Multi-hospital support

## Tech Stack

### Frontend

* Flutter
* Next.js
* Tailwind CSS

### Backend

* Node.js
* Express.js
* Prisma ORM
* Socket.IO
* JWT Authentication

### Database

* PostgreSQL

### Communication

* Exotel Voice API
* Exotel SMS API

## Project Status

🚧 Currently under development.
