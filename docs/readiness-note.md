# Readiness Note

This note is part of the release-readiness audit evidence trail.

- The audit workflow (`.github/workflows/audit.yml`) runs on every push and on manual dispatch.
- It writes a small text file and uploads it as the `audit-evidence` artifact.
- Open audit issues track the release checklist and artifact retention.
- The `evidence-update` branch carries this note; it is proposed via a pull request into `main` and is intentionally left unmerged.
