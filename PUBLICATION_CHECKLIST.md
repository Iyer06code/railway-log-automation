# Public Repository Publication Checklist

## Permission and ownership
- [ ] Confirm whether the client permits public mention of the project.
- [ ] Confirm whether source code, UI screenshots, and project name may be published.
- [ ] Confirm whether client/organization names and operational details must be omitted.
- [ ] If source permission is unclear, publish only the sanitized case study and synthetic demo.

## Source and data review
- [ ] No live Google Sheet, spreadsheet export, backup, or real operational record.
- [ ] No employee names, emails, phone numbers, IDs, signatures, or personal details.
- [ ] No real testing IDs, locations, schedules, incident details, or sensitive operational information.
- [ ] No spreadsheet IDs, Apps Script deployment URLs, internal URLs, or account identifiers.
- [ ] No passwords, API keys, OAuth tokens, private keys, or credential files.
- [ ] No hidden tabs, comments, logs, screenshots, or metadata with confidential details.
- [ ] `.gitignore` reviewed; confirm sensitive files were never committed.
- [ ] Git history reviewed for previously committed secrets or confidential data.
- [ ] If a real credential was exposed, revoke/rotate it.

## Showcase quality
- [ ] README describes the problem, solution, features, technologies, and limitations.
- [ ] Feature claims checked against the delivered version.
- [ ] Screenshots use synthetic data or are explicitly approved for release.
- [ ] Architecture diagram contains no deployment or security-sensitive details.
- [ ] Sample data is fully synthetic.
- [ ] Setup instructions clearly state whether this is runnable or showcase-only.
- [ ] Resume bullet matches the actual work and avoids unmeasured results.

## GitHub settings
- [ ] Repository description and topics added.
- [ ] No license added until code ownership and redistribution rights are clear.
- [ ] Secret scanning and push protection enabled where available.
- [ ] Repository visibility checked before first push.
- [ ] README preview checked after upload.
