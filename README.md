# Osiris

Open-source, self-hosted backup for Microsoft 365 (Exchange Online mail, calendar and
contacts; OneDrive) and IMAP mailboxes, built for IT teams and managed service providers.

A backup only counts once it can be restored. Osiris regularly reads samples of each backup
back and compares them with the stored hashes, and it shows backups that were never verified
as unverified instead of green.

## Status

In development, currently in beta. The source code will be published in this repository.
Archiving (journaling, retention, legal hold) and file-level server backup are planned and
not available yet.

## Licence

AGPL-3.0, see [LICENSE](LICENSE).
