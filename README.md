# EducateShala — AI-Powered School Management SaaS

EducateShala is a modern school management SaaS built for Indian schools, admins, principals, office staff, teachers, students, and parents.

The product brings daily school operations into one secure, role-based platform: school management, user roles, class-section workflows, student records, attendance, homework, exams, fees, notifications, chat, profile management, and AI-assisted admin work.

> This repository is a public case-study and proof-of-work repository for hackathon submission, project review, and portfolio presentation. The private production source code, credentials, database secrets, SMTP keys, and business-sensitive implementation details are not included.

## Hackathon Build Story

I had the idea for EducateShala before the hackathon, but the actual demo-ready SaaS MVP work was started after the hackathon began.

During Hackathon Day 1 to Day 3, I focused on turning the idea into a working MVP direction with:

- A renamed and cleaned EducateShala brand identity
- Local XAMPP-ready PHP/MySQL setup
- Role-based dashboard flows
- School Admin and Super Admin workflows
- Forgot password / OTP flow direction
- AI School Admin Assistant MVP
- Demo-ready UI screens
- Public case-study documentation

The goal was not just to make a static concept, but to show a SaaS-style school operating system that can become useful for real schools.

## Problem

Many schools still manage daily operations using scattered tools, paper records, WhatsApp messages, spreadsheets, and manual follow-ups.

This creates problems like:

- Slow student and staff record management
- Confusing class-section assignments
- Manual attendance and fee tracking
- Delayed parent communication
- No single dashboard for school operations
- Difficulty preparing notices, summaries, and reports quickly

## Solution

EducateShala gives schools one digital operating system for daily administration.

It helps different roles work in their own scoped dashboards:

- **Super Admin** manages schools, subscriptions, platform-level users, support, reports, and audit logs.
- **School Admin / Principal** manages students, teachers, classes, sections, subjects, attendance, homework, exams, fees, notices, and reports.
- **Teacher** manages assigned classes, attendance, homework, marks, messages, and profile.
- **Office Staff** supports student records, fees, receipts, notices, and reports.
- **Parents and Students** access attendance, homework, fees, results, notices, messages, and profiles.

## AI School Admin Assistant MVP

The current hackathon demo includes an AI assistant designed for school operations.

The assistant can help generate:

- School notices
- Student performance summaries
- Class reports
- School workflow answers
- Notification drafts

The AI Assistant is intentionally designed with a safety-first workflow:

- It generates drafts, not automatic sends.
- Admin reviews output before using it.
- Generated notice text can be copied, downloaded, or used as a notification draft.
- Demo mode is clearly labelled when no live AI provider key is configured.

## Demo Screens Covered

The current demo includes screens and flows for:

- School Admin Dashboard
- AI Notice Generator
- AI Student Summary
- AI Class Report
- Admin Help Chatbot
- Recent AI History
- Copy / Download / Use as Notification Draft actions
- Role-based navigation
- EducateShala branding

## Core Modules

- Authentication
- Schools
- Users
- Classes
- Sections
- Subjects
- Students
- Attendance
- Homework
- Fees
- Chat
- Notifications
- Exams
- Marks and Results
- Profile and Settings
- AI Assistant

## Tech Stack

- Core PHP
- MySQL
- XAMPP local development
- HTML
- CSS
- JavaScript
- JWT-style authentication direction
- Role-based access control direction
- Multi-school / school-scoped data model direction

## Security and Privacy Scope

This public repository does not include:

- Production source code
- `.env` files
- SMTP credentials
- API keys
- JWT secrets
- Database passwords
- Admin passwords
- Private business logic
- Real student data

## Current Status

EducateShala is in active MVP development.

The hackathon focus is to demonstrate a school SaaS product direction with an AI-powered school admin assistant and a realistic role-based workflow.

## Pitch Summary

EducateShala is a school operating system for modern India.

It combines school management workflows with AI-assisted admin productivity so that schools can manage records, communication, attendance, reports, and notices faster from one platform.

## Next Roadmap

- Improve role-wise dashboards
- Add stronger production hardening
- Improve mobile parent/student portals
- Add complete report exports
- Add AI-assisted workflows for notices, summaries, and reports
- Prepare staging deployment
- Expand real school testing
