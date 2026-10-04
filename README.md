# 💍 Interactive Royal Digital Wedding Invitation 

A premium, feature-rich, and interactive digital wedding invitation web application built with modern web technologies and real-time backend synchronization. Designed to deliver an immersive RSVP and guest experience.

🌐 **Live Demo:** [https://digital-wedding-invitations.netlify.app](https://digital-wedding-invitations.netlify.app)

---

## ✨ Key Features

* ✉️ **Interactive Envelope Animation:** Smooth wax-seal opening effect with background music auto-trigger.
* ⌛ **Real-Time Countdown Timer:** Dynamic countdown tracking the days, hours, and minutes remaining until the event.
* 📅 **1-Click Google Calendar Integration:** Allows guests to instantly add the wedding schedule to their personal Google Calendar.
* 🗺️ **Google Maps Venue Navigation:** Embedded venue location map for effortless guest navigation.
* 📲 **Automated RSVP with WhatsApp Sync:** Captures guest responses and automatically redirects them to send a pre-formatted Bengali confirmation via WhatsApp.
* 💬 **Live Guestbook / Blessings Board:** Dynamic guest wishes wall where visitors can submit prayers/blessings stored in real-time.
* 📊 **Google Sheets Backend Integration:** Serverless data management using Google Apps Script acting as a lightweight REST API.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+)
* **Backend / Database:** Google Apps Script, Google Sheets API
* **Communication:** WhatsApp Web API (URL Encoding), `Image()` Beacon GET requests for cross-origin data dispatch.
* **Hosting:** Netlify / GitHub Pages

---

## 🚀 How It Works

1. **RSVP Data Flow:** 
   Form inputs $\rightarrow$ Appended to Google Sheets via Apps Script GET Request $\rightarrow$ Instant redirect to WhatsApp with encoded message.
   
2. **Blessings Board Data Flow:**
   User Wish $\rightarrow$ Saved into Google Sheets "Blessings" Tab $\rightarrow$ Dynamic JSON fetch $\rightarrow$ Rendered live on the Guestbook Wall.

---

## 👨‍💻 Author

Developed with ❤️ by **MD Emtiuj Ahmed (Imtiaj)**  
 Portfolio: [imtiaj007.github.io/IA/](https://imtiaj007.github.io/IA/)  
 Focus: AI & Cybersecurity Enthusiast | Web App Development

---
⭐ *If you find this project impressive, feel free to give it a star!*
