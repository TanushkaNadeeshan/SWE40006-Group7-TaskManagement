# Phase 4 — Expanded application checkpoint (reconstructed)
Contains the final application's accounts, project/team management, Kanban, calendar, Gantt, files, analytics, and Node test suites. CI workflow, deployment document and Prometheus configuration are withheld for later checkpoints.

The included Docker Compose file references Prometheus config (omitted at this checkpoint), so run the local `npm run demo` and unit/integration tests rather than enabling the monitoring profile. This represents a **large replacement** of the earlier dashboard, not a small additive feature patch.

Test commands: `npm ci`, `npm ci --prefix backend`, `npm ci --prefix frontend`, `npm run db:init`, `npm test`, `npm run test:integration`, `npm run build`, `npm run demo`. The local demo uses a disposable dataset and requires a valid `backend/.env`.
