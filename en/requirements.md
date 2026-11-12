---
layout: default
lang: en
title: System Requirements
description: Supported platforms for AmetrineVault and what you need to use the sync features.
alt_lang: /requirements/
permalink: /en/requirements/
---

# System Requirements

<p class="meta">Last updated: {{ site.effective_date_en }}</p>

## Supported Platforms

| Platform | Requirement | Available on |
|---|---|---|
| Windows | Windows 10 / 11 (64-bit) | Microsoft Store |
| macOS | macOS 12 Monterey or later (Apple silicon and Intel) | Mac App Store |
| iPad | iPadOS 15 or later | App Store |
| Android tablets | Android 8.0 or later | Google Play |
| Chromebook | ChromeOS with Google Play Store support | Google Play |

- On iPad and Android tablets, the app is designed for **landscape** orientation. Because it shows three panes side by side (tree, editor and outline), it may not display properly on smartphone screens.
- On Chromebook, keyboard and mouse (touchpad) are supported. A touchscreen is not required.

## Display and Language

- Recommended screen width: 1,280 pixels or more
- App language: Japanese (the user interface is currently available in Japanese only)

## Storage

- In addition to the app itself, you need free space for the Markdown files you edit (your Vault) and for the search index. The index grows with the amount of your notes.
- When syncing with Dropbox or SFTP, the contents of the synced folder are also stored on your device (cache). Make sure you have about as much free space as the synced folder.

## Internet Connection

An internet connection is required only for the following. All other features (viewing, editing and searching notes) work offline.

- Signing in, creating an account and resetting your password
- Purchasing and verifying your license (once verified, the license keeps working offline for up to 30 days)
- Syncing with Dropbox or SFTP
- Sending crash reports (can be turned off in Settings)

## Paid Features (Licensed Version)

Dropbox sync and SFTP sync become available after you purchase a license (one-time purchase). An {{ site.app_name }} account (email address and password) is required to purchase and verify the license.

### Dropbox Sync

- A Dropbox account (the free plan is fine)
- Available on: Windows and macOS (iPad and Android support is planned)

### SFTP Sync

- A server you can connect to over SSH (SFTP), and an account on it
- Sign-in methods: password, or private key (OpenSSH or PEM format; passphrase-protected keys are supported)
- When you connect to a server for the first time, the app shows the server's host key fingerprint. Compare it with the fingerprint provided by your server administrator.

## Contact

<a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>
