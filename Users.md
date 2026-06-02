# User Roles and Permissions

This document defines the primary user roles within the Internship Management Platform, outlining their responsibilities, permissions, and typical user journeys.

## Student

### Responsibilities
- Maintain an up-to-date and accurate profile, including resume, skills, and portfolio links.
- Search and apply for relevant internship opportunities.
- Prepare for and attend scheduled interviews.
- Accept or decline internship offers.

### Permissions
- **Create/Edit/Delete:** Own profile, portfolio, and resumes.
- **View:** Available internship postings, application statuses, interview schedules.
- **Perform:** Apply for jobs, withdraw applications, message recruiters (if enabled).

### User Journey
1. **Onboarding:** Registers on the platform using college email, fills out profile, and uploads resume.
2. **Discovery:** Browses the dashboard for recommended internships or searches using filters (domain, location, stipend).
3. **Application:** Applies to selected internships.
4. **Tracking:** Monitors the application status (Applied -> Under Review -> Shortlisted -> Interview -> Offered/Rejected).
5. **Action:** Accepts the final offer and updates the college admin via the platform.

## Recruiter / Company

### Responsibilities
- Create and manage the company profile.
- Post detailed internship opportunities.
- Review student applications and shortlist candidates.
- Schedule interviews and communicate hiring decisions.

### Permissions
- **Create/Edit/Delete:** Company profile, internship postings.
- **View:** Applicant profiles, resumes, and platform analytics related to their postings.
- **Perform:** Change applicant status, send messages/emails to applicants, schedule interviews.

### User Journey
1. **Onboarding:** Registers the company and gets verified by the platform admin.
2. **Posting:** Creates a new internship listing detailing requirements, stipend, and duration.
3. **Review:** Accesses the applicant tracking system (ATS) dashboard to review incoming student applications.
4. **Processing:** Moves candidates through stages (Shortlist, Interview) and schedules interviews.
5. **Hiring:** Extends an offer to the selected candidate(s) and closes the posting.

## College Administrator

### Responsibilities
- Verify student and recruiter registrations.
- Monitor overall placement statistics and student participation.
- Provide support or intervene in case of disputes.
- Manage platform-wide announcements.

### Permissions
- **Create/Edit/Delete:** System settings, announcements, user accounts (admin override).
- **View:** All student profiles, all job postings, comprehensive analytics, and reports.
- **Perform:** Approve/Reject companies, generate placement reports, export data.

### User Journey
1. **Login:** Accesses the secure admin dashboard.
2. **Verification:** Reviews pending approvals for new companies or students and grants access.
3. **Monitoring:** Checks the analytics dashboard to see how many students have applied, been shortlisted, or placed.
4. **Reporting:** Generates a monthly placement report for college management.

---

## Role-Permission Matrix

| Feature / Action | Student | Recruiter | College Admin |
| :--- | :---: | :---: | :---: |
| **Manage Own Profile** | ✅ | ✅ | ✅ |
| **View Internships** | ✅ | ✅ (Own) | ✅ (All) |
| **Post Internships** | ❌ | ✅ | ❌ |
| **Apply for Internships**| ✅ | ❌ | ❌ |
| **Review Applications** | ❌ | ✅ | ✅ (Read-only) |
| **Schedule Interviews** | ❌ | ✅ | ❌ |
| **Verify Users** | ❌ | ❌ | ✅ |
| **View System Analytics**| ❌ | ❌ | ✅ |
| **Export Reports** | ❌ | ❌ | ✅ |
