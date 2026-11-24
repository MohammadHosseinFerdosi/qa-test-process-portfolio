# Evidence and cleanup

## Evidence

- Screenshot or short note on network status
- HTTP status + page title / body snippet (redacted)
- Entity id when relevant
- Monitoring window (e.g. ~3 minutes, ~10s interval)

Narration alone is not evidence.

## Cleanup

After create / delete / mutate tests:

- Remove test entities created during the run
- Confirm consumer surface is healthy again
- If cleanup is blocked (e.g. session expired), state that explicitly
