# TSS CBT Portal — starter prototype

This is a front-end React/Vite prototype for Talented Secondary School (TSS).

## Run locally
1. Install Node.js (LTS).
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite.

## Current prototype features
- Dashboard overview
- Demo student registration (session-only)
- Question bank with multiple-choice question creation
- Examination draft creation and publish/unpublish controls
- Sample student exam preview, countdown, auto-marking
- Demo results table and CSV export
- Admin-controlled result-release setting in the exam list
- Responsive layout for phones and computers

## Important limitations
This is not production-ready and should not be used for real exams yet:
- No backend, database, or secure authentication
- Data resets on page refresh
- Student login fields are not verified
- Word/PDF upload only selects a file; parsing/import is not implemented
- Results are not securely restricted by server permissions
- Timer is browser-side only and can be bypassed
- Exam count/duration and published state are not enforced on a secure server
- No anti-cheating guarantees, backups, or audit log

## Before live deployment
Add a backend and database; secure administrator/teacher/student roles; hash passwords; validate exam PINs server-side; save answers automatically; enforce timers and one submission server-side; implement safe DOCX/PDF extraction with manual review; protect results until admin release; test simultaneous users and backups; publish a privacy notice.
