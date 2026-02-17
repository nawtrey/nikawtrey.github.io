---
title: Automated Lab Reschedule Workflow (Google Apps Script)
order: 5
role: >
  Independently designed and implemented a workflow automation system to reduce recurring administrative email load for undergraduate laboratory instructors.
outcome: >
  Replaced a time-sensitive manual email process with an automated request system that handled approval logic, notifications, and record keeping with minimal instructor maintenance.
problem: >
  Lab instructors were spending significant time handling repetitive, time-sensitive reschedule requests via email. Requests required manual validation, coordination between multiple teaching assistants, and rapid responses, leading to frequent interruptions and substantial administrative overhead.
solution:
  - Built a Google Forms + Apps Script workflow allowing students to submit structured reschedule requests
  - Implemented automated approval logic based on timing rules, section validity, and per-semester request limits
  - Automated email notifications to students, primary lab TAs, and requested lab TAs when applicable
  - Added fallback logic to route communications to instructors when TA information was missing
  - Logged all requests in a shared Google Sheet for transparency and later review
  - Designed the system so instructors only needed to update section IDs and TA emails once per semester
impact:
  - Processed over 2,000 reschedule requests through automated approval and routing workflows
  - Automated 7,400+ email actions, significantly reducing repetitive instructor communication tasks
  - Automatically approved ~80% of requests without instructor intervention
  - Reduced instructor administrative workload by an estimated ~320 staff hours since initial deployment
  - Removed time-sensitive reschedule emails from instructor inboxes, improving focus and workflow continuity
---
