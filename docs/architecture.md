# High-Level Architecture

This conceptual overview intentionally omits client-specific implementation details and deployment identifiers.

```text
User
  |
  v
Google Sheets interface
  |
  v
Google Apps Script logic
  |-- Daily rollover and archive workflow
  |-- Month-specific sheet organization
  |-- Shift and sign-in/sign-out handling
  |-- Access and editing rules
  |
  v
Administrative HTML interface
  |
  v
Authorized maintenance / data correction
```

## Components

- **Google Sheets:** spreadsheet-based interface and record organization.
- **Google Apps Script:** automation and workflow logic.
- **HTML admin interface:** interface for permitted administrative operations.
- **Access rules:** distinguish normal use from administrator actions.

This diagram is illustrative; update it to match the final implementation. Do not publish user emails, internal identifiers, deployment URLs, or permission settings. Do not claim UI-only restrictions are a security boundary unless server-side authorization checks support that claim.
