# Privacy Policy

**Last updated: July 9, 2026**

## 1. Introduction

This Privacy Policy explains how FinanceApp ("the App", "we", "us", or "our") handles your information. We are committed to protecting your privacy and being transparent about our practices.

Please read this policy carefully. By using the App, you agree to the practices described here.

---

## 2. Summary

FinanceApp is a personal finance tracking app designed with privacy at its core:

- **Your financial data is stored on your device**, not on our servers. We cannot see your expenses, income, budgets, savings, or receipts.
- **No account or login is required** to use the App.
- **We do not sell or share your personal data** with advertisers, data brokers, or any third party for their own purposes.
- **Receipts are scanned entirely on your device.** Receipt images are never uploaded.
- A small amount of **technical data** is processed by named service providers to deliver notifications, process purchases, and diagnose crashes — described in detail below. None of it includes your financial records.

---

## 3. Data Stored on Your Device

The App stores the following data **locally on your device**, using your device's local storage. Sensitive items (receipt images and backups) are encrypted with AES-256. This data is not transmitted to us:

- **Financial records**: Expenses, income, fixed expenses, savings entries, recurring transactions
- **Savings goals**: Goal amounts, deadlines, and progress
- **Budget settings**: Monthly budgets and alert thresholds
- **Receipt images and scanned data**: Photos of receipts you scan and the text extracted from them
- **Learned merchant categories**: A local database that improves category suggestions over time
- **Accounts & payment methods**: Account names, currencies, payment method labels
- **Monthly reports**: Summaries generated on your device
- **App settings**: Language, theme, color palette, notification preferences, privacy mode, app-lock settings

You can delete all data at any time from **Settings → Reset Plan**. Uninstalling the App also removes all locally stored data.

---

## 4. Data That Leaves Your Device

We designed the App so your financial records stay with you. The limited information below leaves your device only in the specific circumstances described, and only to the named providers:

| When | What is shared | With whom | Purpose |
|---|---|---|---|
| You enable notifications | An anonymous push token (no personal data) | Expo | Deliver notifications to your device |
| You purchase or restore Premium | An anonymous app-user ID and purchase/subscription status | RevenueCat, Apple, Google | Process and validate your subscription |
| The App encounters an error | Anonymous crash and performance diagnostics (no personal or financial data) | Sentry | Diagnose and fix crashes |
| You contact support | Your email content plus device name/model, OS version, and app version | Sent from your email app to us | Respond to your request |
| You enable backup or export your data | An encrypted backup file | **Your own** iCloud or Google Drive account, or a destination you choose | Back up and restore your data |

**Your financial records are never sent to us or to any of these providers**, except within backups that you place into your own cloud account, which we cannot access.

---

## 5. Camera, Photos & Receipt Scanning

The receipt scanner is optional. When you use it:

- The App requests permission to use your **camera** (to photograph a receipt) or your **photo library** (to import an existing photo).
- Text recognition (OCR) and any QR/barcode reading happen **entirely on your device**, using Apple Vision (iOS) or Google ML Kit. **Receipt images are never uploaded to us or any third party.**
- The resulting receipt image is stored locally on your device, encrypted, and can be deleted at any time by deleting the associated transaction.

You can decline camera and photo permissions and still use every other feature of the App.

---

## 6. Notifications

If you enable notifications, the App uses **Expo's Push Notification Service** to deliver alerts (e.g., budget warnings, savings reminders, spending summaries).

Your device is assigned an anonymous push token by Expo. This token is sent to Expo's servers solely to deliver notifications to your device and contains no personal or financial data. Expo's privacy policy applies: [https://expo.dev/privacy](https://expo.dev/privacy).

You can disable all notifications at any time from **Settings → Notifications**.

---

## 7. Backups & Data Portability

The App lets you back up and restore your data:

- **Cloud backup**: If you enable it, an encrypted backup file is saved to **your own** iCloud (iOS) or Google Drive (Android) account. The backup is encrypted with a key stored securely on your device. We do not operate a backup server and cannot access your backups.
- **Manual export/import**: You can export an encrypted backup file and share or store it wherever you choose using your device's share sheet.

Because backups can be encrypted with a device-held key, restoring on a new device may require that key. Keep your backups safe — we cannot recover them for you.

---

## 8. App Lock & Biometrics

If you enable the app lock, the App can use **Face ID / Touch ID (iOS)** or biometric unlock (Android). Biometric authentication is handled entirely by your device's operating system. The App never receives, stores, or transmits your biometric data.

---

## 9. Contact Support

When you choose to contact support via **Settings → Contact Support**, your default email app opens with a pre-filled message addressed to **finance.app.support01@gmail.com**.

This message automatically includes the following device information to help us diagnose issues:

- Device name and model
- Operating system name and version
- App version

**This information is only sent if you choose to send the email.** You can review and edit the email before sending. We use this information solely to respond to your support request and do not share it with third parties.

---

## 10. Permissions

The App may request the following device permissions:

| Permission | Purpose | Required? |
|---|---|---|
| Camera | Scan receipts by photographing them | Optional |
| Photo Library | Import an existing receipt photo | Optional |
| Notifications | Send budget alerts, savings reminders, and spending summaries | Optional |
| Face ID / Biometrics | Unlock the app when the app lock is enabled | Optional |
| Mail Composer | Open your email app when contacting support | Optional |
| File System / Document Picker | Create and restore encrypted backups | Optional |

No permission is required for the core functionality of tracking expenses and budgets.

---

## 11. Third-Party Services

The App relies on the following third-party services. Each receives only the limited data described in Section 4:

- **Expo (expo.dev)** — The framework the App is built with, and the push-notification infrastructure used when notifications are enabled. Privacy policy: [https://expo.dev/privacy](https://expo.dev/privacy).
- **RevenueCat (revenuecat.com)** — Manages Premium subscriptions. Receives an anonymous app-user ID and purchase status, not your identity or financial records. Privacy policy: [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy).
- **Sentry (sentry.io)** — Anonymous crash and performance diagnostics. Configured to exclude personal identifiers. Privacy policy: [https://sentry.io/privacy](https://sentry.io/privacy).
- **Apple / Google** — Process in-app purchases and, if you enable backup, store your encrypted backup in your own iCloud or Google Drive account.

The App does **not** use advertising networks, does **not** use behavioral analytics or tracking platforms, and does **not** sell or share your data for advertising.

---

## 12. Data Security

- Financial data is stored in your device's local storage.
- Receipt images and backups are encrypted using **AES-256**, with keys held in your device's secure storage.
- Because your data lives on your device, its security also depends on your device's own protections (passcode, biometrics, OS updates). We recommend keeping your device secured and up to date.

No method of storage or transmission is completely secure, and we cannot guarantee absolute security.

---

## 13. Your Rights

Because your financial data is stored on your device and not on our servers, you remain in direct control of it:

- **Access**: All your data is visible within the App at any time.
- **Deletion**: Delete individual records, or erase everything via **Settings → Reset Plan**, or by uninstalling the App.
- **Portability**: Export your data as a backup file at any time.

Depending on where you live (for example, under the EU/UK GDPR or the Swiss FADP), you may have additional rights regarding any personal data a processor holds. For data processed by the services in Section 11, you may exercise those rights directly with each provider, or contact us and we will assist. To make a request or ask a question, email **finance.app.support01@gmail.com**.

---

## 14. Children's Privacy

The App is not directed at children under the age of 13 (or the minimum age required in your country). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information via the contact support feature, please contact us and we will delete it.

---

## 15. Changes to This Policy

We may update this Privacy Policy from time to time. If we make significant changes, we will update the "Last updated" date at the top of this document. We encourage you to review this policy periodically.

---

## 16. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us at:

**Email:** finance.app.support01@gmail.com

---

*FinanceApp is designed to keep your financial life private. Your data belongs to you.*
