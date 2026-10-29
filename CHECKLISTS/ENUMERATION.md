# Enumeration Checklist

Use only against explicitly authorized targets. Record timestamps, scope and evidence in a lab note.

## Scope and setup

- [ ] Confirm target IPs, hostnames, ports and exclusions.
- [ ] Verify VPN/interface and local route.
- [ ] Record timezone and timestamps.
- [ ] Create a sanitized output directory.
- [ ] Understand rate limits and disruptive-action rules.

## Host discovery

- [ ] Determine whether ICMP is allowed or filtered.
- [ ] Identify live hosts using an approved method.
- [ ] Record hostname, MAC/vendor clues and apparent role.
- [ ] Re-check important hosts when conditions change.

## TCP and UDP surface

- [ ] Complete full TCP inventory where permitted.
- [ ] Perform service/version detection on discovered ports.
- [ ] Prioritize UDP checks by likely value and time.
- [ ] Record unexpected or filtered results.
- [ ] Save scan results with exact command and date.

## Service prompts

- DNS: names, records, recursion, transfers and virtual hosts.
- SMB/NetBIOS: shares, naming, signing, metadata and permissions.
- FTP: anonymous access, banners, files and upload/download behavior.
- SSH: version, authentication surface and configuration clues.
- SMTP: banner, permitted commands and enumeration behavior.
- SNMP: exposed information, community handling and version.
- HTTP/HTTPS: technologies, virtual hosts, content, authentication and inputs.
- Databases: version, authentication exposure and permitted metadata.
- Remote administration: protocol, authentication and role clues.

## Prioritization

For every interesting result, record what is known, what is hypothesized, the least-impact validation, proof evidence, and the relevant defensive control or log source.

## Stop conditions

- [ ] Stop if authorization, target identity or scope is unclear.
- [ ] Stop if an action may modify or disrupt a system outside the rules.
- [ ] Escalate when credentials or sensitive data appear unexpectedly.
- [ ] Clean up temporary artifacts and preserve only permitted evidence.
