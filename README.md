# Cleaning Janitorial Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AICleaningJanitorialOperationsAssistant`
- `AICleaningJanitorialOperationsOperations`
- `AICleaningJanitorialOperationsAnalytics`
- `AICleaningJanitorialOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/cleaning-janitorial-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5450`

Seeded users:
- `admin@cleaning-janitorial-operations.local / admin123`
- `manager@cleaning-janitorial-operations.local / manager123`
- `analyst@cleaning-janitorial-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/cleaning-janitorial-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5450 npm run smoke
```
