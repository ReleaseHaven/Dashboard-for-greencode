# RiskMONITOR project dashboard (Team 4, Universidad Austral)

Static one-page dashboard for the Greencode / RiskMONITOR capstone.

- Live data: the n8n workflow "Team 4 - Dashboard data API" (`https://victor3065.app.n8n.cloud/webhook/team4-dashboard-data`) reads the Google Sheet with the Kimai export and returns project-level totals only (no per-person data).
- Shows: cumulative hours vs. estimated hours, progress, hours and revenue per month, hours by activity, hours per task code (RMON-xxx), data-quality flags, and open/closed GitHub issues for any repo you enter.
- Hosting: Vercel deploys `index.html` automatically on every push to `main`.
- The estimate (default 1,200 h) is an assumption (A) until the client confirms the budget.
