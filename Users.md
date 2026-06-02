# User Roles and Permissions

This document defines the primary user roles within the Internship Management Platform, outlining their responsibilities, permissions, and typical user journeys.

---

# Student

## Responsibilities

* Maintain an up-to-date and accurate profile, including resume, skills, and portfolio links.
* Search and apply for relevant internship opportunities.
* Prepare for and attend scheduled interviews.
* Accept or decline internship offers.

## Permissions

* **Create/Edit/Delete:** Own profile, portfolio, and resumes.
* **View:** Available internship postings, application statuses, interview schedules.
* **Perform:** Apply for jobs, withdraw applications, message recruiters (if enabled).

## User Journey

### 1. Onboarding

Registers on the platform using college email, fills out profile, and uploads resume.

### 2. Discovery

Browses the dashboard for recommended internships or searches using filters (domain, location, stipend).

### 3. Application

Applies to selected internships.

### 4. Tracking

Monitors the application status:

Applied → Under Review → Shortlisted → Interview → Offered/Rejected

### 5. Action

Accepts the final offer and updates the college admin via the platform.

---

# Recruiter / Company

## Responsibilities

* Create and manage the company profile.
* Post detailed internship opportunities.
* Review student applications and shortlist candidates.
* Schedule interviews and communicate hiring decisions.

## Permissions

* **Create/Edit/Delete:** Company profile, internship postings.
* **View:** Applicant profiles, resumes, and platform analytics related to their postings.
* **Perform:** Change applicant status, send messages/emails to applicants, schedule interviews.

## User Journey

### 1. Onboarding

Registers the company and gets verified by the platform admin.

### 2. Posting

Creates a new internship listing detailing requirements, stipend, and duration.

### 3. Review

Accesses the Applicant Tracking System (ATS) dashboard to review incoming student applications.

### 4. Processing

Moves candidates through stages (Shortlist, Interview) and schedules interviews.

### 5. Hiring

Extends an offer to selected candidate(s) and closes the posting.

---

# College Administrator

## Responsibilities

* Verify student and recruiter registrations.
* Monitor overall placement statistics and student participation.
* Provide support or intervene in case of disputes.
* Manage platform-wide announcements.

## Permissions

* **Create/Edit/Delete:** System settings, announcements, user accounts (admin override).
* **View:** All student profiles, all job postings, comprehensive analytics, and reports.
* **Perform:** Approve/Reject companies, generate placement reports, export data.

## User Journey

### 1. Login

Accesses the secure admin dashboard.

### 2. Verification

Reviews pending approvals for new companies or students and grants access.

### 3. Monitoring

Checks the analytics dashboard to see how many students have applied, been shortlisted, or placed.

### 4. Reporting

Generates monthly placement reports for college management.

---

# Role-Permission Matrix

| Feature / Action      | Student | Recruiter | College Admin |
| --------------------- | ------- | --------- | ------------- |
| Manage Own Profile    | ✅       | ✅         | ✅             |
| View Internships      | ✅       | ✅ (Own)   | ✅ (All)       |
| Post Internships      | ❌       | ✅         | ❌             |
| Apply for Internships | ✅       | ❌         | ❌             |
| Review Applications   | ❌       | ✅         | ✅ (Read-only) |
| Schedule Interviews   | ❌       | ✅         | ❌             |
| Verify Users          | ❌       | ❌         | ✅             |
| View System Analytics | ❌       | ❌         | ✅             |
| Export Reports        | ❌       | ❌         | ✅             |

---

# Team Members and Contributions

This project was collaboratively prepared by the following team members.

| Name            | Email                                                         | Assigned Role                         | Contributions                                                                                                                                                              |
| --------------- | ------------------------------------------------------------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Arnav Dogra** | [adogra_be23@thapar.edu](mailto:adogra_be23@thapar.edu)       | Project Lead & System Architect       | Led project planning, defined system architecture, prepared user role definitions, designed platform structure, coordinated documentation, and finalized MVP requirements. |
| **Divya**       | [divue2003@gmail.com](mailto:divue2003@gmail.com)             | Business Analyst & Documentation Lead | Gathered requirements, documented platform features, refined user journeys, and reviewed deliverables for consistency and completeness.                                    |
| **Aryan**       | [e23cseu0550@bennet.edu.in](mailto:e23cseu0550@bennet.edu.in) | Workflow & Process Designer           | Designed internship workflows, recruiter hiring process, application lifecycle, and contributed to workflow documentation.                                                 |
| **Akash**       | [akashivaleena@gmail.com](mailto:akashivaleena@gmail.com)     | UI/UX & Wireframe Designer            | Developed wireframes, dashboard layouts, screen flow designs, and contributed to user experience planning.                                                                 |

---

# Team Responsibilities Summary

## Arnav Dogra

* Project planning and coordination
* System architecture design
* User role definition
* MVP planning
* GitHub repository management

## Divya

* Requirement gathering
* Feature documentation
* User stories preparation
* Documentation review

## Aryan

* Workflow design
* Process mapping
* Internship lifecycle modeling
* Application flow documentation

## Akash

* Wireframe preparation
* Dashboard design concepts
* UI/UX planning
* Screen layout documentation

---

## Project Information

**Project Title:** Internship Management Platform

**Team Size:** 4 Members

**Submission Type:** Documentation-Based Design Proposal

**Prepared By:** Team Internship Management Platform

