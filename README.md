# CRM System README

## Overview

Welcome to the Customer Relationship Management (CRM) system! This project is designed to streamline client interactions and internal processes. Built with a React frontend, an Express backend, and MongoDB for data management, the system helps manage contacts, tasks, leads, and more.

## Technical Design

### Frontend (React)
- **Dashboard**: Summarizes sections like contacts, tasks, and leads.
- **Contact/Task Management**: Full CRUD functionalities for managing contacts, tasks, and other resources.

### Backend (Express, MongoDB)
- **API Routes**: CRUD operations for contacts, leads, tasks, etc.
- **Database**: MongoDB collections for contacts, documents, emails, leads, tasks, etc.

## User Interface

### 1. Login
<p align="center">
  <img src="readme_images/login.png" alt="Login Page" width="500">
</p>

### 2. Home Page
<p align="center">
  <img src="readme_images/dashboard.png" alt="Dashboard Page" width="500">
</p>

### 3. Contacts Page
<p align="center">
  <img src="readme_images/contacts.png" alt="Contacts Page" width="500">
</p>

### 3.a Add Contact
<p align="center">
  <img src="readme_images/add_contact.png" alt="Add Contact Page" width="500">
</p>

### 4. Calendar
<p align="center">
  <img src="readme_images/calendar.png" alt="Calendar Page" width="500">
</p>

### 4.a Add Calendar Event
<p align="center">
  <img src="readme_images/add_calendar.png" alt="Add Calendar Event Page" width="500">
</p>

### 5. Documents
<p align="center">
  <img src="readme_images/documents.png" alt="Documents Page" width="500" style="border: 2px solid #000;">
</p>

## Installation Guide

### Prerequisites
- **Node.js**: Install from [Node.js](https://nodejs.org/).
- **MongoDB Compass** or Atlas account.

### Frontend Installation
1. Download and extract project ZIP.
2. Run `npm install` to install dependencies.
3. Set `baseUrl` in `constant.js`.
4. Run `npm start` to launch.

### Backend Installation
1. Download and extract backend ZIP.
2. Run `npm install`.
3. Configure `.env` with MongoDB credentials.
4. Run `npm start` to start the server.

### Default Admin Access (Local)
- **Email**: admin@gmail.com
- **Password**: admin123
