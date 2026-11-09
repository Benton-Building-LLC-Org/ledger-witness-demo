# ledger-witness-demo
The demo ledger's daily witness. MADE-UP data, never the real ledger.

Each day's release holds `head.txt` (the ledger, its position and its head hash, one line) and `head.txt.ots`, its
OpenTimestamps proof; the next day's release carries that proof once Bitcoin confirms it. Releases are immutable.

The first release is 2026-11-09. The daily schedule starts when the witness goes into service, so the days between
the first release and that start have no release: they were never published, not deleted. From the start, every day
has one.
