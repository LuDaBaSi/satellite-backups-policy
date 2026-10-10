
---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Last updated: 10 October 2026**

## 1. Overview

Satellite Backups is a personal project used to maintain backups of selected files and configuration data from a privately operated Debian Linux server.

It is not a commercial service and does not provide backup services to the public.

## 2. Information processed

The backup setup may process files and configuration data selected by the system administrator, including operating system configuration, user files and application data.

The setup uses:

- **Restic** to create encrypted backup repositories and snapshots.
- **rclone** to transfer backup data to Google Drive.
- **Google Drive** to store the remote backup repository.

Google OAuth is used to authorize access to the Google Drive account selected by the account owner.

## 3. Data storage and encryption

Restic encrypts backup repository contents before they are uploaded to remote storage. The repository encryption password is managed separately from the backup repository.

The Google Drive account may expose ordinary operational metadata, such as the existence of the backup folder, file sizes, timestamps and storage usage.

Access to the Google account and the local backup infrastructure is controlled by the account owner.

## 4. Collection and sharing

Satellite Backups does not operate a public server or collect information from website visitors through a dedicated analytics system.

The project does not intentionally sell or disclose backup contents to third parties. Google processes account and service data according to its own terms and privacy policies.

This website is documentation for the project; it does not provide a form, user account system or backup upload service.

## 5. OAuth authorization

The Google Drive integration uses OAuth 2.0 to obtain authorization from the account owner.

The authorization permits the configured rclone application to access Google Drive within the permissions granted by the user. Authorization can be revoked through the user's Google Account security settings.

OAuth credentials and access tokens must not be published in this repository.

## 6. Data retention and deletion

Backup retention and deletion are managed by the system administrator through the Restic repository and Google Drive.

Deleting a local file does not necessarily remove copies already stored in backup snapshots. Remote backups should be deleted deliberately when no longer required.

## 7. Third-party services

This setup relies on services and software maintained by third parties, including Google Drive, Google OAuth, GitHub Pages, Restic and rclone. Their respective terms and privacy policies apply to their services.

## 8. Changes to this policy

This policy may be updated when the architecture or data processing of Satellite Backups changes.

## 9. Contact

For questions about this documentation, contact the owner of the GitHub repository hosting these pages.
