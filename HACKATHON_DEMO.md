# EducateShala Hackathon Demo

## One-Line Pitch

EducateShala is an AI-powered school management SaaS that helps schools manage daily administration, communication, reports, and student workflows from one role-based platform.

## Build Timeline

The idea existed before the hackathon, but the actual demo-ready MVP build work started after the hackathon began.

During Day 1 to Day 3, the focus was to build and document a SaaS-style school platform with:

- EducateShala branding
- School Admin dashboard
- Role-based school workflows
- AI School Admin Assistant MVP
- Notice generator
- Student summary generator
- Class report generator
- School admin help chatbot
- Recent AI history
- Copy, download, and use-as-notification-draft actions

## Demo Flow

### 1. School Admin Dashboard

The dashboard gives the school admin a scoped control panel for managing school members, notifications, attendance, and AI-assisted workflows.

### 2. AI School Admin Assistant

The AI Assistant helps school admins create school-ready drafts and summaries.

It supports:

- AI Notice Generator
- AI Student Summary
- AI Class Report
- Admin Help Chatbot

### 3. Notice Generator

The admin enters a notice topic, audience, language, tone, and notice type.

The assistant generates a formal school-ready notice draft.

The output is not sent automatically. The admin reviews it first.

### 4. Student Summary Generator

The admin or teacher can enter student details such as attendance, marks, and behavior notes.

The assistant generates a parent-friendly student performance summary.

### 5. Class Report Generator

The assistant can turn monthly class observations into a structured report.

This helps schools quickly prepare internal academic summaries.

### 6. Admin Help Chatbot

The chatbot answers workflow questions like:

> How do I add a teacher?

It gives operational steps inside the EducateShala workflow.

### 7. Recent AI History

Generated outputs are shown in recent history, scoped to the school/account.

This helps admins review previously generated notices, summaries, and reports.

## Safety Design

EducateShala AI is designed for school administration, not uncontrolled automation.

Important safety choices:

- AI generates drafts only.
- Sending remains manual.
- Admin review is required.
- Demo mode is clearly labelled.
- No real student data is included in this public case-study repository.

## Why It Matters

Schools often waste time preparing notices, reports, summaries, and communication manually.

EducateShala reduces that work by combining role-based school management with AI-assisted admin drafting.

## Current Demo Limitation

This public repository is a case-study and proof-of-work repository. It does not contain the private production code, secrets, or real school data.

## Next Steps

- Improve UI polish and role-specific dashboards
- Add more production hardening
- Add deployment-ready documentation
- Add real staging demo when safe
- Expand AI workflows for school operations
