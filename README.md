# Tikabula - Ticket Scanner System

## Overview
Tikabula is a comprehensive ticket scanning and attendee management system designed for events, conferences, and venues. The application provides an efficient way to validate tickets via QR codes and manage check-ins with real-time feedback.

## Features
- **QR Code Scanning:** Scan attendee tickets using device cameras
- **Real-time Validation:** Instantly verify ticket authenticity
- **Flashlight Support:** Toggle device flashlight for scanning in low-light conditions
- **Check-in Management:** Track and manage attendee check-ins
- **Admin Dashboard:** Comprehensive administration panel for ticket and account management
- **Responsive Design:** Works on both mobile and desktop devices

## File Structure
```
├── admin/                # Administration panel
│   ├── account_creation.php
│   ├── all_accounts.php
│   ├── all_tickets.php
│   ├── ticket_creation.php
│   └── ...
├── app/                  # Main application
│   ├── check-points.php  # Check-in points management
│   ├── index.php         # Main application entry
│   ├── qr_scanner.php    # QR code scanning functionality
│   └── ...
├── .well-known/          # Domain validation files
└── index.html            # Landing page
```

## 🛠️ Technologies Used

![PHP](https://img.shields.io/badge/Language-PHP-blue)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)
![Tailwind CSS](https://img.shields.io/badge/Framework-Tailwind_CSS-blue)
![Font Awesome](https://img.shields.io/badge/Icons-Font_Awesome-lightgrey)
![Material Design](https://img.shields.io/badge/Icons-Material_Design-lightblue)
![PHPMailer](https://img.shields.io/badge/Email-PHPMailer-green)

- **PHP** - Backend server-side logic
- **JavaScript** - With ZXing library for QR code scanning
- **Tailwind CSS** - Modern, responsive UI
- **Font Awesome** - For icons
- **Material Design Iconic Font** - For additional iconography
- **PHPMailer** - For email notifications

## Setup
1. Clone the repository to your web server directory
2. Set up a PHP environment with MySQL support
3. Import the database schema (if available in the repository)
4. Configure database connection in the configuration files
5. Access the application via web browser

## Requirements
- PHP 7.4 or higher
- MySQL/MariaDB
- Modern web browser with camera access support
- SSL certificate for secure camera access

## Security Notes
- Camera access requires HTTPS in modern browsers
- User authentication should be properly configured
- Database credentials should be properly secured

## License
This project is proprietary.  
Copyright (c) 2025 Sathsindu Induwara (moko@isathsindu.com)  
All rights reserved. Unauthorized use, copying, or distribution is strictly prohibited.

## Credits
- ZXing Library for QR code processing
- Tailwind CSS for styling
- Font Awesome and Material Design Icons for iconography

## Contact
Sathsindu Induwara
moko@isathsindu.com  
