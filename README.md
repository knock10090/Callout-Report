# PSP SERT Callout Report V6.1 — encrypted-draft prototype

Updates: 24-hour time labels and 24-hour Word output, visible app version and local installation-version history, passphrase-based AES-256-GCM encrypted browser drafts, inactivity lock. No Microsoft/OneDrive authentication added.

## Important security limitations
- **Not approved for operational information.** Requires PSP IT/security review and testing.
- Word DOCX exports and share attachments are **not encrypted**. Device downloads and Outlook handling require approved procedures.
- GitHub Pages remains publicly accessible. Encryption protects local drafts, not the app's public availability.
- Passphrase cannot be recovered. Deleting browser storage or reinstalling may lose drafts.
- Native date/time pickers may display AM/PM depending on iOS/Android locale; exported Word output is 24-hour.
- Auto-lock on iOS is best effort; suspended background apps may not run timers.
- Legacy plaintext draft is offered for import after unlocking, then its localStorage entry is removed; removal does not guarantee forensic erasure.
- Existing draft data is not synced across devices.

## Deploy
Unzip all files into GitHub repository root, commit, allow GitHub Pages to update, then fully close and reopen the PWA. Use fictional data for testing.
