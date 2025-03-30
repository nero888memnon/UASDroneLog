# UAS Drone Log App
The UAS Drone Logbook is a browser-based flight tracking application designed for drone pilots to log flight data, manage pilot and aircraft credentials, and monitor compliance with FAA guidelines. Built using HTML, Tailwind CSS, and JavaScript, the app stores all user data locally in the browser, eliminating the need for external databases or servers.

This application supports full user authentication, enabling each pilot to securely manage their own records. Once signed in, users can log individual flight entries with details such as date, flight duration, mission type, and battery performance. The dashboard provides real-time statistics including total flight hours, number of flights, average flight time, and average battery usage.

Pilots can also store their license and drone registration details, with automatic reminders for upcoming expirations. A built-in resources section provides FAA guidelines for safe and legal drone operation, helping users stay informed and compliant.

Key Features
User Accounts & Authentication
Sign-up and sign-in functionality with per-user data stored in localStorage.

Flight Logging System
Record flight date, location, times, purpose, pre-flight checks, battery use, and post-flight notes.

Dashboard Overview
Displays total flights, total flight time, average flight time, and average battery usage.

Profile Management
Store pilot license ID, license expiration, drone registration number, and registration expiration.

Automated Expiration Alerts
Alerts users when license or registration is within 30 days of expiring.

Flight History Table
View previous logs with date, location, duration, battery usage, and notes.

FAA Resources Section
Includes a summary of FAA rules, tips, and a link to the official FAA UAS site.

Responsive UI
Fully mobile-friendly and styled using Tailwind CSS for a clean, modern layout.

Offline-Ready
Runs entirely in the browser without a backend—data is saved to the device.

