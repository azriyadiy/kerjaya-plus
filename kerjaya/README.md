# Kerjaya+ — Complete Localhost Prototype

## What this version adds
- Separate `index.html`, `css/style.css`, and `js/app.js`.
- Node.js backend using only the built-in `http` module (no external web framework required).
- Persistent JSON database in `data/db.json`.
- Login, demo login and registration API.
- Job search/filtering and skill-based match calculation.
- Save job and apply job APIs.
- Application records and status updates.
- Training course enrolment records.
- Employer job-post API and applicant API.
- Government dashboard summary API.
- Responsive frontend based on the existing Kerjaya+ prototype.

## Requirements
Node.js 18+.

## Run
```bash
npm install
npm start
```
Then open `http://localhost:3000`.

## Demo accounts
- Jobseeker: `demo@kerjaya.plus` / `demo123`
- Employer: `employer@kerjaya.plus` / `demo123`
- Government: `gov@kerjaya.plus` / `demo123`

## Important
This is a fully functional **local prototype**, not a production government employment system. OTP, payments, certificate verification, real employer integrations, cloud hosting, production security, and real government datasets still need external services and deployment configuration.
