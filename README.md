# BiziNovate – Tech Bootcamp Website

## 📌 Project Overview

BiziNovate is a startup tech business/bootcamp platform designed to empower aspiring technology professionals through structured learning programs in:

* Web Development
* Cybersecurity
* Software Engineering (Future Expansion)

This website serves as the official online platform for marketing bootcamps, managing student registrations, and issuing certificates upon course completion.

This is the MVP (Minimum Viable Product) version built using frontend technologies and deployed on Netlify.

---

## 🎯 Project Goals

* Present BiziNovate as a professional tech startup
* Display available bootcamps and pricing
* Allow students to apply online
* Provide a student login dashboard
* Generate a downloadable certificate upon course completion
* Deploy a live production-ready website
* Also display events that is hosts 

---

## 🛠️ Tech Stack

Frontend:

* HTML5
* CSS3
* JavaScript (Vanilla JS)

Deployment:

* Netlify

Additional Library:

* html2pdf.js (for certificate PDF generation)

---

## 📁 Project Structure

```
/index.html          → Home Page
/about.html          → About Page
/bootcamps.html      → Courses Page
/pricing.html        → Pricing Page
/apply.html          → Application Form
/login.html          → Student Login
/dashboard.html      → Student Dashboard
/certificate.html    → Certificate Page

/css/                → Stylesheets
/js/                 → JavaScript files
/images/             → Images and assets
```

---

## 🚀 Features

### 🌐 Public Pages

* Professional landing page
* Founder spotlight section
* Bootcamp overview
* Pricing table
* Responsive design
* Call-to-action sections

### 📝 Application System

* Student application form
* Form validation
* Confirmation message

### 🔐 Student Login (MVP)

* Simulated authentication using localStorage
* Student session handling
* Dashboard access

### 📊 Student Dashboard

* Displays student name and enrolled course
* Course completion simulation
* "Mark as Complete" functionality
* show in progress course

### 🎓 Certificate System

* Dynamically generates certificate using:

  * Student Name
  * Course Name
  * Unique Certificate ID
* Downloadable as PDF using html2pdf.js

---

## 📄 Certificate Logic (MVP)

Since this version does not include a backend or database:

* Student data is stored in localStorage
* Completion is simulated via dashboard button
* Certificate is generated dynamically on the frontend
* Certificate ID format example:

  ```
  BZN-2026-WD-0001
  ```

⚠️ Note: This certificate system is for MVP purposes only and is not secure for production-level verification.

---

## 👥 Team Responsibilities

### Developer 1 – System & Logic

* JavaScript functionality
* Login system
* Dashboard logic
* Certificate generation
* Deployment setup

### Developer 2 – UI/UX & Design

* Layout design
* Branding and color palette
* Responsive styling
* Certificate visual design
* User experience improvements

---

## 📅 Development Timeline

### Week 1

* Page structure completed
* Styling finalized
* Responsive design implemented

### Week 2

* Login system completed
* Dashboard functionality implemented
* Certificate generation working
* Deployment to Netlify

---

## 🔮 Future Improvements (Phase 2)

* Backend integration (Node.js / Firebase / Supabase)
* Secure authentication system
* Database for storing students
* Admin dashboard
* Certificate verification system
* Online payment integration
* Course progress tracking
* Video learning modules

---

## 🌟 Vision

BiziNovate aims to become a leading tech bootcamp platform that prepares students for real-world technology careers through hands-on learning and practical experience.

---

## 📢 Status

Current Version: MVP
Deployment: Netlify
Project Type: Startup Website

---

## 📬 Contact

For business inquiries, partnerships, or enrollment information, please contact BiziNovate through the official website contact form.

---

© 2026 BiziNovate. All Rights Reserved.


## Coming later on ...

This whole website will be updated by including the backend also the database so that the information of the customers/student can be stored
and saved
