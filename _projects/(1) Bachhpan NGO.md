---
name: Bachhpan – NGO Management Android Application
tools: [Android SDK, Java, SQLite, XML]
image: \assets\Bachhpan NGO.jpg
description: An Android application designed for the NGO Bachhpan to streamline Pathshala management, including attendance tracking, student performance monitoring, volunteer scheduling, and campaign management.
---

### Overview
Bachhpan is an Android application built to help Bachhpan NGO manage Pathshalas where volunteers teach underserved students, replacing manual processes with structured, data‑driven workflows across attendance, tests, syllabus, volunteer planning, and campaigns. 

### Problem
Pathshalas were managed manually with no standardized parameters to analyze student or volunteer performance, resulting in non‑uniform subject coverage, scarcity or misallocation of volunteers, and inefficient use of physical and financial resources. 

### Goals
- Create a common mobile interface for all stakeholders to unify information flow and planning.
- Capture structured data to analyze patterns in attendance, subject coverage, and test outcomes. 
- Plan volunteers effectively to ensure the right coverage on the right days. 

### Key features
- Dashboard: Post sharing and moderation for activities across Pathshalas, with role‑based approvals and bookmarks.
- Campaign Manager: Create campaigns, define venue/date/duration, invite targeted volunteers, and record day‑of interest signups. 
- Pathshala Directory: Browse Pathshalas with student/volunteer counts and addresses; admins can add/remove Pathshalas. 
- Students: Search, filter, sort; add/remove with passphrase; capture school/class/parents/contact details. 
- Volunteers: Search, filter, sort; add/remove authorized volunteers; capture college, email, ID/address, and contact. 
- Attendance: One‑touch attendance entry by Pathshala/class/date with subject/chapter tags and visual summaries. 
- Subjects & Syllabus: Track taught vs. untaught chapters with graphs per class. 
- Tests: Record marks by subject/chapter; visualize distribution and min/max achievers. 
- Planner: Shared calendar for volunteer availability to avoid under/over‑staffing. 

### Roles and access
- Random user: View Dashboard and browse entities; no data edits. 
- Volunteer/Teacher: Post, view/bookmark, attendance, planner, and tests as permitted.
- Media committee: Broad read/write similar to volunteers for content workflows. 
- Pathshala representative: Full operational modules including approvals.
- College head/Alumni: Oversight and read access; alumni have limited write scope. 
- Admins: Full create/update/delete across modules and approvals. 

### Data model and flows
- Entities: Pathshala, Student, Volunteer, Post, Campaign, Attendance, Subject, Chapter, TestResult. 
- Flows: Login/Signup, Dashboard moderation, Campaign creation/notifications, Attendance/Test entry, and Performance reporting with graphs. 

### UI highlights
- Login screen with email/contact and password authentication. 
- Performance Sheet tabs for Attendance, Tests, and Subjects with bar graph visualizations and scoped filters. 

### Tech stack
- Android SDK **(Java, XML layouts), SQLite** for offline‑first structured storage and fast local queries; role gating within app layers. 

### Impact
The app standardizes Pathshala operations, enabling consistent attendance capture, equitable subject coverage, volunteer scheduling, and measurable student performance—reducing planning friction and improving resource utilization. 