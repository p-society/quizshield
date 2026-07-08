# Secure Quiz Platform with Screenshot Protection (Web + App)

## Introduction

With the rapid growth of online assessments in education and recruitment, ensuring the integrity and fairness of quizzes has become a major challenge. Traditional online quiz systems are vulnerable to malpractice methods such as screenshots, screen recording, and unauthorized content sharing.

This project proposes a **Secure Quiz Platform** that integrates DRM-like protections and anti-cheating mechanisms to reduce unauthorized capture and distribution of quiz content. The platform will support both **Web** and **Mobile** applications while sharing a common backend architecture for scalability, maintainability, and consistency.

---

# Problem Statement

Existing online quiz platforms lack robust mechanisms to prevent:

- Screenshot capture during quizzes
- Screen recording or mirroring
- Content leakage through unauthorized sharing

These limitations result in:

- Unfair evaluations
- Reduced credibility of assessments
- Increased opportunities for cheating

---

# Objectives

The primary objectives of this project are:

- Develop a secure online quiz platform with anti-cheating mechanisms
- Implement screenshot blocking and detection techniques wherever supported
- Support both Web and Mobile applications
- Maintain a unified backend architecture
- Provide real-time monitoring and logging of suspicious activities

---

# Scope of the Project

The platform will include:

- Web-based quiz application
- Mobile application (Android/iOS)
- Backend APIs for authentication, quiz management, and monitoring
- Admin dashboard for quiz creation, management, and analytics

---

# System Architecture

| Layer | Technology |
|--------|------------|
| Web Frontend | React / Next.js |
| Mobile App | React Native / Flutter |
| Backend | Node.js + Express |
| Database | PostgreSQL / MongoDB |
| Authentication | JWT / OAuth |
| Security Layer | DRM-like controls, secure rendering, event tracking |

---

# Features

## User Features

- Secure Login & Signup
- Timed Quiz Attempt
- Automatic Submission on Timeout
- Tab Switch Detection (Web)
- Screenshot Detection / Prevention (Mobile)
- Real-time Quiz Experience

---

## Admin Features

- Create, Edit and Delete Quizzes
- Add MCQ and Subjective Questions
- Configure Timer, Difficulty and Access Rules
- Live Monitoring of Quiz Attempts
- View Results and Analytics

---

## Security Features

- Screenshot Blocking (where platform supports it)
- Tab Switching Detection
- Window Minimize / Focus Loss Detection
- Screen Blur on Focus Loss
- Dynamic Watermarking (User ID / Email)
- Suspicious Activity Logging
- Audit Trail for Security Events

---

# Engineering Challenges

## Screenshot Prevention

- Web browsers cannot completely block screenshots.
- Mobile operating systems provide different levels of protection.
- The platform will rely on prevention, detection, watermarking, and deterrence techniques.

---

## Cross-Platform Consistency

- Different APIs and security capabilities across Web and Mobile.
- Maintaining a consistent user experience.

---

## Real-Time Monitoring

- Efficiently monitoring large numbers of concurrent quiz sessions.
- Logging suspicious events without affecting performance.

---

## Security vs User Experience

- Excessive restrictions may negatively impact usability.
- The platform should balance security and accessibility.

---

## Backend Scalability

- Handle high numbers of simultaneous quiz attempts.
- Prevent server overload during peak assessments.

---

# Expected Deliverables

## Software

- Web Application
- Mobile Application
- Backend REST API
- Database Schema
- Admin Dashboard

---

## Documentation

- System Design Document
- API Documentation
- User Manual
- Testing & Validation Report

---

## Demonstration

- Live Quiz Attempt
- Screenshot Protection Demonstration
- Tab Switch Detection
- Focus Loss Handling
- Admin Monitoring Dashboard

---

# Repository Structure (Planned)

```text
.
├── backend/
├── frontend/
├── mobile/
├── docs/
└── .github/
```

---

# Future Enhancements

- AI-based cheating detection
- Webcam proctoring
- Face recognition
- Browser lockdown mode
- End-to-end encrypted assessments
- Detailed analytics dashboard
- Institution and classroom management
- Question randomization engine
- Secure exam browser integration

---

# Status

🚧 **Project is currently under active development.**

Contributions, suggestions, and discussions are welcome.
