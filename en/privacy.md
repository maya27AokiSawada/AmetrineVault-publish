---
layout: default
lang: en
title: Privacy Policy
description: What information AmetrineVault handles and how it is used, stored and deleted.
alt_lang: /privacy/
permalink: /en/privacy/
---

# Privacy Policy

<p class="meta">Effective date: {{ site.effective_date_en }}</p>

{{ site.provider_en }} (the "Provider") handles information about users of the app "{{ site.app_name }}" (the "App") in accordance with this Privacy Policy.

## Summary

- **The content of your notes is never sent to the Provider.** Notes are stored only on your device or on a storage location you specify (Dropbox or an SFTP server).
- You create an account only when you purchase or verify the paid features (License). In that case, we handle your email address and License information.
- We do not show ads or use tracking for usage analytics. We do not sell your information.
- Crash reports are sent only after removing note content, file names and paths. You can turn them off in Settings.

## 1. Information Stored Only on Your Device

The following information is stored on your device and is not sent to the Provider.

| Information | Where it is stored |
|---|---|
| Notes (Markdown files) and the search index | Device storage (the folder you choose and the App's own folder) |
| Copies of files synced from Dropbox or SFTP (cache) | The App's own folder |
| Settings (color theme, last opened folder, etc.) | The App's own folder |
| Dropbox access token | The operating system's secure storage (Keychain, Windows DPAPI, etc.) |
| SFTP connection details, and the passwords, private keys and passphrases you choose to save | Connection details: the App's own folder / Secrets: the operating system's secure storage |
| The email address used to sign in (if you choose to save it), and when the License was last verified | The operating system's secure storage |
| Activity logs | The App's own folder. Passwords, tokens and similar values are masked |

Your App account password is not stored on your device.

## 2. Information Handled by the Provider's Services

### 2.1 Account and License

If you create an account to purchase or verify the paid features, we handle the following information.

| Information | Purpose |
|---|---|
| Email address, password (stored in hashed form; the Provider cannot read it), account identifier, email verification status, sign-up and last sign-in times | Sign-in, identity verification, password reset |
| License information (plan, status such as active or refunded, purchase date, purchase channel) | Checking whether you can use the paid features |
| Store purchase identifiers (such as transaction IDs) | Verifying purchases, preventing duplicate use, handling refunds |

This information is managed with Firebase (Firebase Authentication and Cloud Firestore), provided by Google LLC.

### 2.2 Purchases

Payments in the Stores are processed by each Store (Apple, Google or Microsoft). The Provider does not receive payment information such as credit card numbers.

### 2.3 Crash Reports

When the App crashes or an unexpected error occurs, the App sends the following information to Sentry, provided by Functional Software, Inc., so that we can investigate the cause.

- The type of error and where in the program it occurred
- Technical information such as the App version, operating system and version, and device model
- Performance statistics (for a sample of launches and operations only)

Before sending, the App **removes note content, file names, folder paths, your computer user name, email addresses and tokens**. Screenshots and records of your interactions are not sent. The App is not configured to use your IP address to identify you.

Crash reports are on by default. **You can turn them off at any time in the App's Settings**, after which no further reports are sent.

## 3. Communication with Third-Party Services

When you use the paid features, the App communicates directly from your device with the following parties. This communication does not pass through the Provider.

- **Dropbox** (Dropbox, Inc.): lists, downloads and uploads files within the scope you authorize. Dropbox's handling of information is governed by the [Dropbox Privacy Policy](https://www.dropbox.com/privacy).
- **SFTP servers**: the App connects to the server you specify to list, download and upload files. The handling of information on that server is governed by the policies of its administrator.

When the App displays an HTML file, it may communicate with external hosts if that HTML loads external resources such as images. Links in the page open in your device's default browser.

## 4. How We Use Information

The Provider uses the information it collects only for the following purposes:

1. Managing accounts, verifying identity and resetting passwords
2. Verifying Licenses and handling purchases and refunds
3. Investigating and fixing bugs, and improving quality
4. Responding to inquiries and sending important notices (such as changes to the terms or discontinuation of the service)
5. Preventing fraudulent use

## 5. Disclosure to Third Parties and Service Providers

The Provider does not disclose your information to third parties except:

- With your consent
- As required by law
- When necessary to protect a person's life, body or property and it is difficult to obtain your consent

For the purposes above, we entrust the handling of information to the following service providers.

| Service provider | Role | Country |
|---|---|---|
| Google LLC (Firebase) | Account and License management | United States |
| Functional Software, Inc. (Sentry) | Storing and analyzing crash reports | United States |

These providers are located in the United States, whose data protection regime differs from Japan's. The Provider uses them after confirming the data protection measures they provide (data processing agreements, encryption, access controls, etc.).

## 6. Retention

- Account and License information: until you delete your account. However, purchase records may be retained for the period required by tax and accounting laws.
- Crash reports: up to 90 days after receipt.
- Information on your device: until you delete the App or delete it within the App.

## 7. Security

Communication is encrypted (HTTPS and SSH). Passwords, tokens and private keys stored on your device are kept in the operating system's secure storage. For SFTP, you confirm the host key the first time you connect to a server, and the App will not automatically connect to a server whose key differs from the recorded one.

## 8. Your Rights

You may request access to, correction of, suspension of use of, or deletion of your information held by the Provider. Please contact us at the address below. After verifying your identity, we will respond without undue delay in accordance with applicable law.

If you live in the European Economic Area, the United Kingdom, California or another jurisdiction with similar laws, you may exercise the rights provided by those laws (such as access, rectification, erasure, restriction of processing, data portability and objection), and you may lodge a complaint with your local supervisory authority. The Provider processes information on the basis of performance of a contract (account and License) and legitimate interests (improving quality through crash reports).

## 9. Account Deletion {#account-deletion}

You can request deletion of your account without the App, as follows:

1. From the email address registered to your account, send an email to <a href="mailto:{{ site.contact_email }}?subject={{ site.app_name | uri_escape }}%20account%20deletion">{{ site.contact_email }}</a> with the subject "{{ site.app_name }} account deletion".
2. After verifying your identity, we will delete your account, as a rule within 30 days, and notify you by email when it is done.

What is deleted: your email address, password, account identifier and License information.

What is retained: purchase records that must be kept under tax and accounting laws (only for the legally required period). Crash reports are not linked to your account and are deleted when their retention period (up to 90 days) expires.

Please note: once your account is deleted, any License linked to it can no longer be used, and this cannot be undone. Refunds for Store purchases are subject to each Store's policy. Notes on your device are not deleted (notes in the folder you chose remain even if you delete the App).

## 10. Children

The App is not directed to children under 13 (or a higher age where required in your country). If we learn that we have collected information from such a child, we will delete it promptly.

## 11. Changes to this Policy

The Provider may change this Policy as needed. We will notify you in advance on this page or in the App before making significant changes.

## 12. Contact

- Provider: {{ site.provider_en }}
- Contact: <a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>

The Japanese version of this Policy is the governing version. This English version is a translation provided for reference; in case of any discrepancy, the Japanese version prevails.
