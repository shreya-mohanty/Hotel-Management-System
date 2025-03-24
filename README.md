# 🏥 Hospital Management System - SQL Schema
This project contains the SQL schema for a Hospital Management System, designed to manage patients, doctors, appointments, medical histories, and scheduling efficiently.

## 📁 Schema Overview
- The schema includes the following core entities:

- Patient & Doctor Tables: Store user info with login credentials

- Appointment System: Handles scheduling, patient visits, and diagnoses

- Medical History: Links to patient and doctor for history tracking

- Doctor Schedules: Manages working hours and availability

## 🛠 Technologies Used
- PostgreSQL

- SQL DDL (Data Definition Language)

## 📦 Tables Included
- patient, doctor, appointment, medical_history

- patient_visits, patients_history, diagnose

- schedule, doctor_schedules, doctor_view_history

## 🚀 How to Use
- Copy and run the SQL script in your PostgreSQL database.

- It will create a hospital_management schema with all required tables and relationships.

- Foreign keys ensure data consistency between related tables.

## 📌 Notes
- Includes CASCADE drops for clean re-creation.

- Some demo integration with online_retail_app.user_login table is shown.
