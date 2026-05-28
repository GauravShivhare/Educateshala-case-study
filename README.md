# EducateShala — AI-Powered School Management SaaS MVP

EducateShala is a school management SaaS MVP built for schools, admins, principals, office staff, teachers, students, and parents.

It brings daily school operations into one secure, role-based platform: school management, user roles, class-section workflows, student records, attendance direction, homework direction, exams, fees direction, notifications, chat direction, profile management, and AI-assisted school admin work.

> This is a public case-study and proof-of-work repository for hackathon submission, project review, and portfolio presentation. The private production source code, credentials, database secrets, SMTP keys, and business-sensitive implementation details are not included.

---

## Hackathon Submission Links

### GitHub Case Study

https://github.com/GauravShivhare/Educateshala-case-study

### Demo Assets: Video + Pitch Deck

Google Drive folder containing the Day 4 demo walkthrough video and pitch deck:

https://drive.google.com/drive/folders/13ZZSOKpGRwS6laB7Tr4loYVHHDeyveSZ?usp=drive_link

### Important Review Note

The full source code is private because EducateShala is an active SaaS/startup project. This repository is intended to show:

- What was built
- Product direction
- MVP screenshots/demo flow
- Pitch deck and demo video
- Feature list
- Tech stack
- User flow
- Local setup explanation
- Security/privacy decisions

---

## Hackathon Build Story

I had the idea for EducateShala before the hackathon, but the actual demo-ready SaaS MVP work was started after the hackathon began.

During Hackathon Day 1 to Day 3, I focused on turning the idea into a working MVP direction with:

- A renamed and cleaned EducateShala brand identity
- Local XAMPP-ready PHP/MySQL setup
- Role-based dashboard flows
- School Admin and Super Admin workflows
- AI School Admin Assistant MVP
- Template AI Mode for reliable demo output
- Demo-ready UI screens
- Product screenshots
- Pitch deck
- Demo walkthrough video
- Public case-study documentation

The goal was not just to make a static concept, but to show a SaaS-style school operating system that can become useful for real schools.

---

## Problem

Many schools still manage daily operations using scattered tools, paper records, WhatsApp messages, spreadsheets, and manual follow-ups.

This creates problems like:

- Slow student and staff record management
- Confusing class-section assignments
- Manual attendance and fee tracking
- Delayed parent communication
- No single dashboard for school operations
- Difficulty preparing notices, summaries, and reports quickly
- Repeated workflow questions for admins and teachers

---

## Solution

EducateShala gives schools one digital operating system for daily administration.

It helps different roles work in their own scoped dashboards:

- **Super Admin** manages schools, platform-level users, support, reports, and audit direction.
- **School Admin / Principal** manages students, teachers, classes, sections, subjects, attendance, homework, exams, fees, notices, and reports.
- **Teacher** manages assigned classes, attendance, homework, marks, messages, and profile direction.
- **Office Staff** supports student records, fees, receipts, notices, and reports.
- **Parents and Students** access attendance, homework, fees, results, notices, messages, and profiles direction.

---

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
- The MVP uses **Template AI Mode** for stable demo output without external API keys.
- Live AI provider support can be added later.

---

## Demo Screens Covered

The current demo includes screens and flows for:

- School Admin Dashboard
- AI Assistant home screen
- Template AI Mode badge
- AI Notice Generator input and output
- AI Student Summary output
- AI Class Report output
- Admin Help Chatbot output
- Recent AI History
- Copy / Download / Use as Notification Draft actions
- Role-based navigation
- EducateShala branding

Recommended screenshots folder:

```text
EducateShala_Phase1_Screenshots/
```

Screenshots are available in `EducateShala_Phase1_Screenshots/`.

The pitch deck is available in `pitch-deck/EducateShala_AI-Powered_School_Administration.pdf`.

The demo video is linked externally through the demo assets folder and/or `DEMO.md`. The MP4 is intentionally not committed to GitHub.

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

---

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
- Template AI Mode for demo reliability
- Codex + AI tools for building, testing, verification, and documentation

---

## User Flow

```text
Login
  → School Admin Dashboard
  → AI Assistant from Sidebar
  → Template AI Mode badge visible
  → Choose tool
      → Notice Generator
      → Student Summary
      → Class Report
      → Admin Help Chatbot
  → Enter safe demo input
  → Generate output
  → Review output
  → Save to History / Copy / Download / Use as Notification Draft
```

More detail is available in [`USER_FLOW.md`](USER_FLOW.md).

---

## Local Setup Explanation

The private MVP runs locally on XAMPP with PHP and MySQL.

Local architecture direction:

```text
Browser → Apache/XAMPP → PHP APIs → MySQL → JSON response → Dashboard UI
```

The public repository does not include private source code or secrets. It provides a reviewable case-study package instead.

More detail is available in [`LOCAL_SETUP.md`](LOCAL_SETUP.md).

---

## Demo Guide

The project can be reviewed using:

1. This GitHub case-study repository
2. Demo video in the Google Drive folder
3. Pitch deck in the Google Drive folder
4. Product screenshots
5. User flow and local setup documentation

More detail is available in [`DEMO.md`](DEMO.md).

---

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
- Database dumps
- Full private app ZIP files
- Local video exports
- Dependency folders such as `vendor/` or `node_modules/`

---

## Current MVP Status

EducateShala is in active MVP development.

The hackathon focus is to demonstrate a school SaaS product direction with an AI-powered school admin assistant and a realistic role-based workflow.

Current demo status:

- Working local MVP walkthrough recorded
- Pitch deck prepared
- Template AI Mode verified
- AI Assistant flow demonstrated
- Product screenshots prepared
- Case-study repository prepared

---

## Pitch Summary

EducateShala is a school operating system for modern India.

It combines school management workflows with AI-assisted admin productivity so that schools can manage records, communication, attendance direction, reports, and notices faster from one platform.

---

## Next Roadmap

- Improve role-wise dashboards
- Add stronger production hardening
- Improve mobile parent/student portals
- Add complete report exports
- Connect live AI providers after safety checks
- Add AI-assisted workflows for notices, summaries, and reports
- Prepare staging deployment
- Expand real school testing
