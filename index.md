---
layout: default
title: Lakshya — Privacy Policy
---

# Lakshya — Privacy Policy

**Effective date:** 24 April 2026
**App:** Lakshya — NEET & JEE Countdown
**Package name:** `com.lakshya.app`
**Developer contact:** support@aurabyt.com

---

## Summary

Lakshya is a fully offline study companion for NEET and JEE aspirants. It does **not** collect, store, share, transmit, or sell any personal information. There is no account, no login, no analytics, no advertising SDK, and no network permission.

Everything you do inside Lakshya — chapter progress, confidence ratings, mock test scores, quiz attempts, streaks, and settings — stays on your device.

---

## Data we collect and share

| Category | Collected? | Shared? |
|---|---|---|
| Personal info (name, email, phone, address) | No | No |
| Financial info | No | No |
| Location | No | No |
| Contacts | No | No |
| Messages / photos / media / files | No | No |
| Device or other identifiers | No | No |
| App activity, browsing, or search history | No | No |
| Installed apps | No | No |
| Health / fitness data | No | No |
| Anything else | No | No |

**We collect nothing. We share nothing.**

---

## Where your data lives

All app data is written to your device's private app storage by Android:

- **Progress, mocks, quizzes, stats** — stored in a local Room (SQLite) database at `/data/data/com.lakshya.app/databases/`.
- **Preferences** (selected exam, reminder opt-in, language) — stored via Android DataStore at `/data/data/com.lakshya.app/files/`.
- **Exports** — when you tap "Export JSON" in Settings, a file is written to the app's cache directory and shared via Android's share sheet to the destination *you* pick. The exported file is deleted on the next app launch.

Uninstalling the app wipes all of the above.

---

## Permissions we request

- **`POST_NOTIFICATIONS`** (Android 13+, optional) — only if you opt in to the daily study reminder from Settings. You can revoke it at any time from Android system settings. Notifications are scheduled locally on your device using WorkManager; nothing is sent over the network.

We do **not** request the `INTERNET` permission. The app cannot connect to the internet even if asked to.

---

## Backups

Android may include Lakshya's local data in the device's automatic cloud backup (Google Drive) if you have device backup enabled in Android settings. This is a standard Android feature and is controlled entirely by you. You can disable it system-wide in **Settings → Google → Backup** or for this app only in **Settings → Apps → Lakshya → Storage**.

Lakshya does not send data to Google directly; it only marks certain files as backup-eligible per [Android's backup rules](https://developer.android.com/guide/topics/data/autobackup).

---

## Children's privacy

Lakshya is designed for students aged 13 and older preparing for NEET or JEE entrance exams. Because the app collects no data of any kind, it collects no data from children. The app is not directed at children under 13 and has no social features, advertising, user-generated content, or in-app purchases.

---

## Third-party SDKs

Lakshya uses no third-party analytics, advertising, crash reporting, attribution, or user-tracking SDKs. The app's only third-party dependencies are open-source Android libraries (Jetpack Compose, Room, Hilt, WorkManager, Kotlin coroutines, Glance) that run entirely on-device and do not make network requests on the app's behalf.

---

## Your rights

Because we store nothing about you, there is nothing for us to delete on a server. To erase your local data:

- **Reset progress** — Settings → Reset progress (planned for v1.1)
- **Full wipe** — Uninstall the app, or go to Android Settings → Apps → Lakshya → Storage → Clear data.

You can also export your local data to a JSON file from Settings → Export at any time.

---

## Changes to this policy

If Lakshya's behavior ever changes in a way that affects user privacy (for example, adding an optional cloud sync feature), this page will be updated and the app's "What's new" release notes will call it out explicitly.

---

## Contact

For privacy questions, write to **support@aurabyt.com**.
