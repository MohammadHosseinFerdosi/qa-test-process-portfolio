# Test management — cases vs cycles

## Cases vs cycles

- **Test cases** — durable specs (steps + expected result)
- **Test cycles** — an execution window against a build/environment

An old Fail on a case is not the latest truth if a newer cycle retested it. Keep the case library and execution results separate when updating verdicts.

## Result rules

| Verdict | When to record it |
| --- | --- |
| Pass | Oracle matched + evidence |
| Fail | Mismatch + bug link / comment |
| Blocked | Named dependency; not a silent skip |

## Automation note

Private automation repos may sync case keys and push collector results into a test-management tool. Credentials and company project keys stay out of this repository.
