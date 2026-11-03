# Test design checklist

1. Equivalence partitions — one representative per class
2. Boundaries — min/max, empty, just-inside / just-outside
3. Risk order — money, auth, PII, irreversible mutations, concurrency first
4. Paths — happy, negative, edge (empty, race, timeout, partial failure)

Prefer fewer high-signal cases over near-duplicate checklists.
