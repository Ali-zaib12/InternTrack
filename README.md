# InternTrack 🎯

A full-stack web application that helps university students organize and track 
their internship applications in one place.

## Features
- 🔐 User authentication with JWT and bcrypt
- 📋 Add, edit, delete and filter internship applications
- 📊 Dashboard with live stats (total, interviews, offers, pending)
- ⭐ Company reviews with star ratings
- 🔍 Search applications by company, role or location
- 📄 Export applications to PDF

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Authentication:** JWT + bcryptjs
- **Frontend:** HTML, CSS, Vanilla JavaScript

## Setup
1. Clone the repo
2. Run `npm install`
3. Import `schema.sql` into MySQL
4. Copy `.env.example` to `.env` and fill in your details
5. Run `npm run dev`
6. Open `http://localhost:3000`
