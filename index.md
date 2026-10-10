
---
layout: default
title: Satellite Backups
permalink: /
---

# Satellite Backups

**Personal backup infrastructure documentation**

Satellite Backups is a personal backup setup designed to protect configuration files and selected data from a Debian Linux home server.

The setup uses:

- **Restic** to create versioned, encrypted backups.
- **rclone** to transfer backup data to Google Drive.
- **Google Drive** as an off-site backup destination.

## Purpose

This project documents the configuration used to maintain personal backups and improve data recovery resilience.

The Google Drive integration is authorized by the account owner and is used to manage backup repository data.

## Security

Backup repository contents are encrypted by Restic before being transferred to remote storage. The encryption password is managed separately and is not stored in this public repository.

Access to Google Drive is authorized through Google's OAuth 2.0 process.

## Intended use

Satellite Backups is a personal-use project. It is not a public backup service and does not offer services to third parties.

## Privacy

For information about the data processed by this setup, see our [Privacy Policy](/privacy/).
