# Roadmap

Third of the three new packages (neozp decision D5). Its brief waits until Confab has a real job (neozp roadmap I4), so it starts from that code.

## What the brief will start from

- Confab, which today runs `auth.Sweep` in a bare goroutine. Its iteration 4 (neozp roadmap I4) adds a real job: a call for papers that closes at a date.
- zp's scheduler, read as a record of needs: cron and ISO 8601 schedules, executions stored in the database, overlap strategies, recovery of missed runs, a reaper for stale tasks, worker pools, and idempotency keys for side effects that must not run twice.

## M0: the brief

| ✓ | Item | Done when |
|---|---|---|
| ☐ | M0.1 `docs/brief.md`: what the record of needs teaches, the idea, decisions (each marked epistemer or Claude), the API sketch, open questions with defaults | written |
| ☐ | M0.2 A review by the other model family | its findings fixed or answered |
| ☐ | M0.3 Spikes for the risky decisions | each recorded as an ADR |
| ☐ | M0.4 `docs/interface.md`, locked by epistemer | locked; build milestones planned here |

Ownership: [ownership.md](ownership.md), delegated by epistemer on
2026-11-24.
