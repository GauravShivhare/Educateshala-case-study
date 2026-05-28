# EducateShala AI Assistant User Flow

This user flow represents the current Day 4 hackathon MVP flow.

## Flow Diagram

```mermaid
flowchart TD
    A[Login with demo school admin] --> B[School Admin Dashboard]
    B --> C[AI Assistant from Sidebar]
    C --> D[Template AI Mode Badge Visible]
    D --> E{Choose AI Tool}

    E --> F[AI Notice Generator]
    E --> G[AI Student Summary]
    E --> H[AI Class Report]
    E --> I[Admin Help Chatbot]

    F --> J[Enter notice topic, audience, language, tone, type]
    G --> K[Enter student name, class, attendance, marks, behavior note]
    H --> L[Enter class, month, attendance, strong/weak subjects, teacher notes]
    I --> M[Ask school workflow question]

    J --> N[Generate Template Output]
    K --> N
    L --> N
    M --> N

    N --> O[Review AI Output]
    O --> P[Save to Recent AI History]
    O --> Q[Copy Output]
    O --> R[Download .txt]
    O --> S[Use as Notification Draft]

    S --> T[Manual review before sending]
```

## Current MVP Behavior

- The assistant runs in Template AI Mode.
- No external AI provider is required for the demo.
- Generated outputs are drafts and are not sent automatically.
- Recent outputs are saved in AI History.
- Copy and Download actions are available.
- Student and Parent roles are blocked from AI Assistant access.

## Demo Flow Summary

```text
Dashboard → AI Assistant → Choose Tool → Enter Input → Generate Output → Review → Copy / Download / History / Notification Draft
```
