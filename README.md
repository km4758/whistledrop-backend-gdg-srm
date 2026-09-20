# WhistleDrop Backend
Anonymous reporting API with random case codes, reporter-facing tracking, moderator authentication, filtering, status workflow and validation.

Run: npm install && ADMIN_TOKEN=strong-secret npm start
Endpoints: POST /reports, GET /reports/:caseCode, GET /moderator/reports, PATCH /moderator/reports/:caseCode, GET /health.

No reporter identity is accepted, stored or returned. Production should use persistent encrypted storage and a secret manager.