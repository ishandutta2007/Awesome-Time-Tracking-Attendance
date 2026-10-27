# Awesome-Time-Tracking-Attendance

## Top Time Tracking & Attendance Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Timesheet Management, Shift Scheduling & Workforce Attendance*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Time Tracking & Attendance**. These tools enable organizations to record employee work hours, manage shifts and schedules, track leave balances, and generate payroll-ready timesheets—ensuring accurate compensation and compliance with labor regulations.



**Examples** include Workday Time Tracking, ADP Workforce Now, UKG Ready, Kronos (UKG Workforce Central), Replicon, Clockify, Harvest, Toggl Track, Deputy, and QuickBooks Time (the category leaders).



**Open-source emphasis**: This section covers active projects for self-hosted attendance tracking and timesheet management—ideal for organizations building sovereign workforce time infrastructure without per-seat or per-employee licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Time Tracking](https://www.workday.com/)**  

  Time tracking within Workday's HCM suite, integrated with payroll, scheduling, and absence management for unified workforce data.



- **[ADP Workforce Now](https://www.adp.com/)**  

  Payroll and HCM platform with time and attendance capabilities, including scheduling, absence tracking, and integration with ADP's payroll engine.



- **[UKG Ready](https://www.ukg.com/)**  

  All-in-one HR, payroll, and workforce management suite with time tracking, scheduling, and compliance features for small to mid-sized businesses.



- **[Kronos (UKG Workforce Central)](https://www.ukg.com/)**  

  Enterprise workforce management platform with time and attendance, scheduling, and labor analytics; widely deployed in healthcare, retail, and manufacturing.



- **[Replicon](https://www.replicon.com/)**  

  Time tracking and workforce management platform with timesheet approvals, project time allocation, and payroll integration.



- **[Clockify](https://clockify.me/)**  

  Free time tracker with unlimited users, project tracking, timesheets, and reporting; popular for its generous free tier.



- **[Harvest](https://www.getharvest.com/)**  

  Time tracking and invoicing platform for teams and freelancers, with project budgets and billable rate management.



- **[Toggl Track](https://toggl.com/track/)**  

  Simple cross-platform time tracking with one-click timers, project tagging, and reporting for individuals and teams.



- **[Deputy](https://www.deputy.com/)**  

  Workforce management platform with shift scheduling, time tracking, and payroll integration for hourly workforces.



- **[QuickBooks Time](https://quickbooks.intuit.com/time-tracking/)**  

  Time tracking (formerly TSheets) integrated with QuickBooks for payroll, job costing, and employee scheduling.



## Open-Source GitHub Projects



- **[Frappe HR](https://github.com/frappe/hrms)**  

  Comprehensive open-source HRMS built on the Frappe Framework, covering the full employee lifecycle including **Attendance & Time Tracking** with biometric integration and automated check-in/out . The **Shift Management** module supports shift types, shift requests, shift assignments, and Employee Checkin processing with **Auto Attendance** that marks attendance based on check-in records once the shift's actual end time passes . Attendance Device ID can be mapped for biometric/RFID integration . Docker-deployable and integrates naturally with ERPNext.



- **[Horilla HRMS](https://github.com/horilla/horilla-hr)**  

  Free and open-source HR management system (Django) with modules for recruitment, onboarding, **Attendance & Time Tracking**, leave, payroll, and performance . Attendance features include biometric integration and automated check-in/out . The Docker image (`horilla/horilla-hr`) supports PostgreSQL and is deployable via Compose .



- **[Skapp](https://github.com/SkappHQ/skapp)**  

  Open-source people management and HR platform (AGPL) for growing teams, featuring employee directory, leave management, and **Attendance & Time Tracking** with clock in/out, timesheet management, attendance reports, and manual time entry adjustments . Built with React/TypeScript frontend, Node.js/NestJS backend, PostgreSQL, Redis, and Elasticsearch . Gold Award Winner at APICTA 2025 .



- **[Kimai](https://github.com/kimai/kimai)**  

  Leading open-source time-tracking application (GPL-3.0) for freelancers, agencies, and teams; records timesheets with customers, projects, and activities, generates invoices, and provides 30+ reports . Features multi-user/multi-team support, REST API, webhooks, plugin marketplace (including LDAP/SSO), and 2FA . Docker and Railway deployment options available .



- **[EmpRoster](https://wordpress.org/plugins/employee-roster/)**  

  Self-hosted WordPress plugin for staff scheduling and attendance; features visual weekly/monthly roster views, shift creation with direct or open-slot assignment, **clock in/out attendance with break tracking**, leave requests with manager approval, shift swap requests, and payroll calculations . All data stays on your WordPress server with no SaaS dependency .



- **[iobroker.time-tracker](https://www.npmjs.com/package/iobroker.time-tracker)**  

  Open-source time tracking adapter for ioBroker with employee punch in/out, corrections with audit trail, a kiosk terminal for badge and PIN punches, a live "who is at work" presence board, and REST API . Role-based access distinguishes employees, managers (punch/correct for others), and admins . Suitable for small teams wanting a self-hosted punch clock with IoT integration.



- **[MosP](https://github.com/es-mind/MosP/)**  

  Open-source attendance management system (AGPLv3, Java) from Japan, web-based for intranet or internet use; features history management tracking who, when, and where . First released in 2006 and actively maintained; suitable for organizations needing a mature Japanese-language attendance system.



### Additional Strong Open-Source Options



- **@classytic/muster** — Framework-agnostic attendance primitive (npm package) supporting check-in/out, breaks, corrections, and multiple methods (kiosk, QR, RFID, biometric, facial, mobile, geofence); storage-agnostic with MongoDB integration, suitable for developers building custom attendance systems .

- **TimeTracker (DRYTRIX)** — Self-hosted time tracking with persistent server-side timers, invoicing, unlimited users, and Docker deployment for NAS or cloud .



**Frameworks for building custom systems**: Combine **Frappe HR** for full HRMS with shift management and auto-attendance from biometric check-ins, **Kimai** for detailed project time tracking and invoicing, **Skapp** for a modern HR platform with attendance tracking, and **EmpRoster** for WordPress-based shift scheduling with clock in/out in a self-hosted time and attendance stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Time tracking and attendance platforms handling employee data must comply with applicable labor laws (overtime rules, break requirements), payroll regulations, and data privacy requirements (GDPR, CCPA); attendance records may be subject to regulatory retention.

- Self-hosted open-source solutions vary in scope—Frappe HR and Horilla provide full HRMS with attendance, while Kimai focuses on project timesheet billing and EmpRoster targets WordPress-based scheduling; full enterprise time and attendance with complex pay rules, union compliance, and multi-country labor law support typically requires commercial platforms.

- Verify license terms for commercial use; Frappe HR uses Frappe's licensing, Horilla is open-source, Skapp uses AGPL, Kimai uses GPL-3.0 , and MosP uses AGPLv3 .



---



**Made for HR operations teams, payroll managers, workforce administrators, and time tracking practitioners.**  

Let's make time tracking and attendance more open, accurate, and worker-friendly.
