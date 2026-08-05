---
title: "Week 6 Worklog"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:
* Research AWS Cognito authentication mechanism.
* Integrate Backend REST APIs, sync authentication state, and push production builds to AWS Organization.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study Amazon Cognito (User Pools, Identity Pools, JWT Tokens). <br> - Get temporary backend environment parameters (API URL, Cognito Region, User Pool ID, Client ID). <br> - Add AWS Cognito SDK and integrate into React login flow for Authentication state management. | 07/06/2026 | 07/06/2026 | |
| 3 | - Update environment variables. <br> - Refactor Login/Sign-in logic to authenticate via AWS Cognito User Pool SDK. | 07/07/2026 | 07/07/2026 | |
| 4 | - Integrate RESTful APIs with Backend API endpoints. <br> - Replace Mock Data with live API calls using `VITE_API_URL`. <br> - Integrate APIs for Dashboard, Tasks, Kanban, Calendar, Timeline, Statistics, Saved Filters, Workflow, and Import/Export. | 07/08/2026 | 07/10/2026 | |
| 5 | - Optimize error handling and API feedback states (loading, success, error notifications). <br> - Refine frontend code to integrate smoothly with backend API payload models. | 07/09/2026 | 07/09/2026 | |
| 6 | - Deploy static build assets to S3 and invalidate CloudFront CDN cache on AWS Organization. <br> - Perform full end-to-end testing between Frontend and Backend APIs (CRUD tasks, filter, workflows, JSON/CSV exports). <br> - Fix CORS sharing issues. | 07/10/2026 | 07/12/2026 | |

### Week 6 Achievements:

* Successfully synced frontend application pages with RESTful APIs and AWS Cognito authentication.
* Successfully deployed Frontend application to AWS Organization environment.