# Defensive and Ethical Scope Notes

## Authorization first

Only test systems when you have clear permission from the owner or an authorized program. A public IP, exposed service or guessed credential is not permission.

Confirm exact targets and exclusions, dates, time windows, rate limits, permitted techniques, data handling, emergency contact and stop conditions before starting.

## Keep practice safe

- Use isolated labs, snapshots and throwaway accounts.
- Prefer the least-impact validation that proves a hypothesis.
- Do not exfiltrate real personal, financial or business data.
- Do not commit credentials, tokens, private keys or customer data.
- Sanitize hostnames, usernames and addresses in public notes.
- Remove temporary artifacts and restore lab state.

## Defensive perspective

For every technique, ask what log, alert or network control could reveal it, which hardening change would prevent it, what evidence is sufficient without unnecessary collection, and how a defender could validate the fix.

## Stop and escalate

Stop when scope or authorization is ambiguous, a target appears different from the approved target, sensitive data is encountered, or an action may cause instability. Preserve minimum permitted evidence and contact the authorized owner.

## Repository hygiene

Keep this knowledgebase to educational notes and sanitized lab evidence. Do not commit malware, live-target secrets, or material that bypasses an explicit scope boundary.
