# GCP Incident Response Runbook

## 1. Detection
- Use Cloud SCC, log-based alerts, and SIEM detections.
- Confirm the incident severity.

## 2. Containment
- Label affected resources: `incident=IR-2025-001`
- Isolate VMs:
  - Remove external IPs.
  - Apply quarantine firewall rules.
- Capture snapshots for forensics.

## 3. Eradication
- Identify root cause.
- Patch vulnerabilities.
- Revoke compromised credentials.

## 4. Recovery
- Restore services in a clean state.
- Monitor for reinfection.

## 5. Post-Incident Review
- Document timeline, impact, and root cause.
- Identify improvement actions.
- Update runbook and detection rules.
