# PSP SERT Callout Report V6.3

Changes: Keeps V6 mobile layout, 24-hour labels and Word export, and app version tracking. Removed the encrypted vault, passphrase, automatic lock, and the security-warning paragraph from the form. Drafts now save locally without encryption. No authentication or hosting changes.

**Important:** This version does not encrypt drafts or exported Word documents. GitHub Pages remains publicly accessible. Do not enter operationally sensitive information without department approval.

**Migration:** Previous encrypted V6.1 vault data is left untouched but cannot be opened by V6.3. If you need it, use V6.1 and its original passphrase to export it before switching. Older plaintext drafts may be restored automatically.

## Deploy
Unzip all files to the GitHub repository root, replacing matching files, and commit. Reload the installed app after Pages updates.

V6.3: Added clipping containers and inline-size containment around all native iOS date and datetime-local inputs to prevent overflow beyond their form cards. Military-time export, version history, and no-password behavior unchanged.
