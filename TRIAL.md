# First instructor simulation · October 27, 2026

This is a scripted/operator evaluation, not genuine learner evidence.

A fresh GitHub template copy was SSH-cloned. Setup installed a new local virtual
environment; Black, Pylint, 85 non-E2E tests and two real Docker/Chromium tests
passed. The existing host had 15 containers and an unused studio hostname.

The first launch created its calculator container but immediately rejected the
new route's temporary self-signed certificate. The CLI then mislabeled the
helper failure as an SSH problem. Normal trusted HTTPS succeeded shortly after;
subsequent verify passed release identity, production health, 6×7=42, division
by zero 400 and numeric-string rejection 422. Its selected preservation check
found the other 15 container identities, states and published ports unchanged.
See [dated sanitized evidence](studio/evidence.json).

Fixes prompted: bounded trusted-TLS readiness for a new route; preserve the
actual helper error; avoid repeated JSON reports; shorten the student spec;
clarify manual PR creation, CI without local Docker, and final pull/status.
The first launch did not save a successful new-launch report. This later report
correctly says already-managed, not newly launched.

Passive coaching replies were scripted. Learner explanations remain Pending in
LEARNING.md; the runtime success did not cause status to claim completion.
The temporary deployment will be removed and this disposable repository archived
before repeating with the corrected template.
