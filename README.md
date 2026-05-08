# EthicalProject

## Overview
EthicalProject is a cybersecurity demonstration project focused on understanding and simulating brute-force attacks using wordlists from SecLists in a controlled and ethical environment. The project was developed for educational purposes to help students and cybersecurity enthusiasts learn how brute-force attacks work, how attackers use password dictionaries, and how systems can defend against such attacks.

The application demonstrates how automated login attempts are performed using large password collections while emphasizing ethical hacking practices, defensive security awareness, and responsible testing.

---

## Features

- Brute-force attack simulation
- Integration with SecLists wordlists
- Automated credential testing
- Login request handling
- React-based frontend dashboard
- Backend attack processing
- Educational cybersecurity demonstration
- Security awareness training
- Real-world attack workflow simulation

---

## Technologies Used

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Security Resources
- SecLists password dictionaries
- HTTP request automation

### Deployment
- Vercel

---

## What is SecLists?

:contentReference[oaicite:0]{index=0} is a widely used collection of multiple types of lists used during security assessments, penetration testing, and ethical hacking. It contains:
- Password wordlists
- Username lists
- URL discovery lists
- Payload collections
- Fuzzing data

This project uses SecLists password dictionaries to demonstrate how weak passwords can be discovered through brute-force techniques.

---

## How the Project Works

1. The React frontend provides a user interface for managing brute-force simulations.
2. The backend loads password wordlists from SecLists.
3. Automated login attempts are performed against a target authentication system.
4. The backend analyzes server responses for successful authentication.
5. Results and statistics are displayed in the frontend dashboard.

This demonstrates:
- The danger of weak passwords
- The importance of rate limiting
- Account lockout protection
- Multi-factor authentication (MFA)
- Secure authentication design

---

## Project Structure

```bash
EthicalProject/
│
├── frontend/              # React frontend application
├── backend/               # Brute-force logic and API handling
├── wordlists/             # SecLists password dictionaries
├── README.md
└── .gitignore
