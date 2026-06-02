# Minimum Viable Product (MVP) Definition

This document outlines the strategy and scope for the Minimum Viable Product of the Internship Management Platform.

## Project Goal
To launch a functional, reliable, and user-friendly platform that allows students to successfully apply for internships and enables companies to post jobs and track applicants efficiently.

## Core Functionalities (The "Must-Haves")
1. **User Authentication:** Secure login and registration for Students, Recruiters, and Admins.
2. **Student Profiles:** Ability for students to create a profile and upload a PDF resume.
3. **Company Profiles & Job Posting:** Ability for recruiters to create a company page and post internship details.
4. **Job Board & Search:** A centralized listing of all active internships with basic search functionality.
5. **Application System:** Students can apply to jobs; recruiters receive applications.
6. **Basic Applicant Tracking (ATS):** Recruiters can move applicants through simple stages (Applied -> Shortlisted -> Hired/Rejected).

## User Stories
* **As a Student**, I want to search for internships by role so that I can find relevant opportunities.
* **As a Student**, I want to apply with one click using my saved profile so that I save time.
* **As a Recruiter**, I want to view a list of all applicants for my posting so I can review their resumes.
* **As a Recruiter**, I want to update an applicant's status to "Shortlisted" so I can keep track of potential hires.
* **As an Admin**, I want to approve new company registrations to ensure legitimacy and prevent spam.

## Success Metrics
* **User Acquisition:** 500 student registrations and 20 company registrations within the first month.
* **Engagement:** At least 3 applications submitted per active student.
* **Platform Health:** 99.9% uptime and a page load speed of under 2 seconds.
* **Task Success Rate:** 90% of recruiters can successfully post a job without assistance.

## Assumptions
* Students and recruiters have access to modern web browsers.
* Colleges are willing to promote this platform to their student body.
* Recruiters are open to using a new platform for their hiring needs.

## Out of Scope Features (Post-MVP)
* In-app messaging/chat system.
* Video interviewing tools.
* Advanced AI resume parsing and matching.
* Complex data export and custom reporting.
* Mobile applications (iOS/Android).

## Implementation Timeline (Estimated)
* **Week 1-2:** UI/UX Design, Database Schema Setup, Authentication module.
* **Week 3-4:** Development of Student and Company Profile modules.
* **Week 5-6:** Job Posting, Search, and Application Flow development.
* **Week 7:** Basic Admin Dashboard and Notification system.
* **Week 8:** Testing (QA), Bug Fixing, and MVP Launch.

## Risk Analysis
| Risk | Impact | Mitigation Strategy |
| :--- | :--- | :--- |
| **Low Student Adoption** | High | Partner directly with college placement cells for mandatory onboarding. |
| **Fake Job Postings** | High | Implement manual admin approval for all new company accounts. |
| **Scope Creep** | Medium | Strictly adhere to the defined MVP MoSCoW prioritization. |
| **Data Privacy Issues** | High | Ensure GDPR/CCPA compliance, encrypt sensitive data, and use secure auth (JWT). |

## Conclusion
The MVP focuses on establishing the core connection between students and recruiters. By stripping away complex auxiliary features, we ensure a faster time-to-market and provide a solid foundation for future iterations based on real user feedback.
