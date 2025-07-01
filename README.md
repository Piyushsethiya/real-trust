# Real Trust – Full Stack Development Task

### By: Piyush Sethiya

---

## Overview

This project is a full-stack web application that includes a landing page and an admin panel for managing projects, clients, contact form details, and newsletter subscriptions. The backend and frontend are integrated to handle data, and features are implemented as per the requirements specified.

---

## Features

### Landing Page:

1. **Our Projects Section**: 
   - Displays a list of all projects fetched from the backend.
   - Each project includes:
     - Project’s Image
     - Project’s Name
     - Project’s Description
     - A dummy Read More button (Non-functional)

2. **Happy Clients Section**: 
   - Displays all clients fetched from the backend.
   - Each client includes:
     - Client’s Image
     - Client’s Description
     - Client’s Name
     - Client’s Designation

3. **Contact Form**:
   - Allows users to submit the contact form with the following details:
     - Full Name
     - Email Address
     - Mobile Number
     - City
   - The form submits data to the backend for storage and viewing in the admin panel.

4. **Newsletter Subscription Section**:
   - Users can enter their email address to subscribe to the newsletter.
   - The email address is sent to the backend.

### Admin Panel:

1. **Project Management**:
   - Admin can add new projects by providing:
     - Project’s Image
     - Project’s Name
     - Project’s Description

2. **Client Management**:
   - Admin can add new client details, including:
     - Client’s Image
     - Client’s Name
     - Client’s Description
     - Client’s Designation (e.g., CEO, Web Developer)

3. **Contact Form Details**:
   - Admin can view all the submitted contact form responses, including:
     - Full Name
     - Email Address
     - Mobile Number
     - City

4. **Subscribed Email Addresses**:
   - Admin can view all email addresses subscribed to the newsletter.

### Additional Features:

1. **Image Cropping**:
   - When images are uploaded from the admin panel, they can be cropped to a specific ratio (e.g., 450x350) before being stored in the backend.

---

## Installation Instructions

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/Piyushsethiya/real-trust
   ```

2. Navigate to the project folder.

   ```bash
   cd <project-folder>
   ```

3. Install dependencies.

   ```bash
   npm install
   ```

4. Set up your environment variables for the backend (MongoDB Atlas, PORT, etc.).

5. Run the backend server.

   ```bash
   node app.js
   ```

---

## Technologies Used

- **Frontend**: HTML, CSS, Javascript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas (Free Tier)
- **Deployment**: Render

---
