# Onion Data Labs: pre-registration fingerprints

This repository records SHA-256 fingerprints of the test plans (pre-registrations) behind the
results Onion Data Labs publishes. Each plan is written down and committed before its test runs.
Its fingerprint is posted here, in a dated public commit, before the test starts.

When a result is published, its test plan is published with it. Anyone can then check that the
published plan has the fingerprint recorded here, in a commit dated before the test ran:

```bash
shasum -a 256 PREREGISTRATION.md   # or: sha256sum PREREGISTRATION.md
```

A fingerprint reveals nothing about the plan's content. A plan can be amended before its test
runs; each amended version gets its own record, and the commit history keeps every one.

Questions or corrections: info@oniondatalabs.com
