# System Workflows

This document details the core processes of the platform using Mermaid diagrams.

## 1. Student Internship Application Flow

This workflow illustrates how a student discovers and applies for an internship, and tracks their application.

```mermaid
flowchart TD
    A[Student Login] --> B[View Dashboard]
    B --> C{Search or Browse?}
    C -->|Search| D[Apply Filters]
    C -->|Browse| E[View Recommendations]
    D --> F[View Internship Details]
    E --> F
    F --> G{Interested?}
    G -->|No| B
    G -->|Yes| H[Click Apply]
    H --> I[Select/Upload Resume]
    I --> J[Submit Application]
    J --> K[Application in 'Applied' State]
    K --> L[Track Status on Dashboard]
```

## 2. Recruiter Hiring Flow

This workflow shows how a recruiter posts a job, reviews applications, and extends an offer.

```mermaid
flowchart TD
    A[Recruiter Login] --> B[Dashboard]
    B --> C[Post New Internship]
    C --> D[System Publishes Job]
    D --> E[Wait for Applications]
    E --> F[Review Applicant List]
    F --> G{Assess Candidate}
    G -->|Reject| H[Move to Rejected]
    G -->|Shortlist| I[Move to Shortlisted]
    I --> J[Schedule Interview]
    J --> K[Conduct Interview]
    K --> L{Interview Outcome}
    L -->|Fail| H
    L -->|Pass| M[Extend Offer]
    M --> N[Candidate Accepts/Declines]
```

## 3. Admin Monitoring Flow

This workflow demonstrates how an administrator oversees platform activities and verifies users.

```mermaid
flowchart TD
    A[Admin Login] --> B[Admin Dashboard]
    B --> C{Select Action}
    C -->|View Metrics| D[Generate Placement Reports]
    C -->|Manage Users| E[View Pending Approvals]
    E --> F{Review Company Profile}
    F -->|Valid| G[Approve Company]
    F -->|Invalid/Spam| H[Reject/Ban Company]
    C -->|Manage Content| I[Review Flagged Job Posts]
    I --> J{Violates Policy?}
    J -->|Yes| K[Remove Job Post]
    J -->|No| L[Ignore/Approve]
```
