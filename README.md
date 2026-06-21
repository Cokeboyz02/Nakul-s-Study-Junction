# Nakul's Study Junction - Student Dashboard

This student portal dashboard provides a sleek and clean interface designed for effective student registration management. Built with a modern dark cinematic theme, it features a touch of liquid glass UI and robust automated workflows.

---

Features

*   Liquid Glass UI: Enjoy a premium, modern design leveraging custom CSS filters, backdrop blurs, and delicate drop shadows for a visually stunning appearance across all devices.
*   Cloudinary HD Photo Sync: Seamlessly upload student profile photos directly to Cloudinary in full HD resolution in the background using an unsigned upload preset.
*   Smart Image Compression (Fallback): Built-in canvas engine instantly compresses uploaded images for efficient use in the navbar, optimizing page speed and bandwidth.
*   Seamless Reverse-Loop Video Background: Custom JavaScript creates a fluid video playback experience that intelligently rewinds and loops the background video without interrupting the flow, circumventing mobile browser limitations.
*   Formspree Integration: Effortlessly collect essential student data including name, validated email, HD photo link, and thumbnail data, directly into your Formspree inbox.

---

Tech Stack

*   Frontend: HTML5, CSS3, JavaScript (ES6)

*   Styling Framework: Tailwind CSS

*   Typography & Icons: Instrument Serif (Google Fonts) & Lucide Icons

*   Media Cloud Storage: Cloudinary Server

*   Form Handler: Formspree API

---

How to Set Up & Customize

# 1. Upload to GitHub

Upload your files to your GitHub repository. Remember to include your index.html.

# 2. Connect Your Cloudinary Accounts

Replace the default Cloudinary variables in index.html to use your own cloud storage for student photos:

``javascript

// Replace with your actual Cloudinary account details

const CLOUDNAME = 'YOURCLOUDINARYCLOUDNAME';

const UPLOADPRESET = 'YOURUNSIGNEDUPLOADPRESET';
