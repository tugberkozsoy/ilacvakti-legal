---
layout: default
title: Privacy Policy
permalink: /privacy-en/
---

# MedTime (İlaçVakti) — Privacy Policy

**Last updated:** October 4, 2026

MedTime (İlaçVakti) is a mobile application developed by Pharmacist **Mehmet Tuğberk Özsoy**, designed to help users track their medications. Your privacy is our top priority; this policy transparently explains what data is processed and how.

Turkish version: [privacy-tr](/ilacvakti-legal/privacy-tr/)

---

## 1. Data Not Collected

MedTime does **not** collect personal identifiers (name, email, phone, ID number, date of birth, etc.) from users, does not send them to our servers, and does not share them with third parties. No account creation is required; the app works entirely **anonymously**.

Detailed list of data not collected:
- ❌ Ad networks, profiling or cross-app tracking (for App Store ad measurement, see Section 5)
- ❌ Third-party analytics services (Google Analytics, Facebook Pixel, etc.)
- ❌ Location data
- ❌ Contacts, calendar
- ❌ Storing audio recordings (the microphone is only activated for optional voice entry, see 3.6)
- ❌ Account creation, email, phone
- ❌ Apple Health data **never leaves** your device (the optional read/write sync runs on-device, see 3.5)
- ❌ Your iCloud backup and family sharing data **never reach** the developer (they stay in your own iCloud accounts, see 2.1 and 2.2)

---

## 2. Local Storage (Data Kept on Your Device)

The information you enter is stored **on your device's internal memory**; the developer has no server that holds this data:

- Medication names, dosages, reminder times
- Profile names (names you provide) and optional profile photo
- Medication stock information and photos
- Treatment history, taken/skipped logs
- Streak and badge data
- Manually added health reports and notes
- Theme, language, notification sound, and settings preferences

When you delete the app, this data is removed from your device. If iCloud backup is on, your backup stays in your own iCloud account (see 2.1).

### 2.1 iCloud Backup (on by default, can be turned off)

If you are signed in to iCloud on your iPhone, the app saves a backup of your data once a day to **the private area of your own iCloud account** (Apple CloudKit private database). This brings your medicines and history back when you change phones or reinstall the app.

- The backup contains medicines, profiles, reports, readings, dose history, badge/streak information and app settings. **Photos are not included.** Readings imported from Apple Health are not included either; Apple Health keeps them itself and the app reads them again on a new phone.
- The backup is stored in Apple's end-to-end encrypted fields (CloudKit encrypted values); the encryption key is in your iCloud Keychain. Very large backups (years of history) are kept as an encrypted file in iCloud; with Advanced Data Protection on, this file is end-to-end encrypted as well.
- The backup never goes to the developer's servers; **the developer cannot access your backup.** It uses your iCloud storage.
- The list of your family sharing connections (who you follow, who sees your doses) is backed up the same way, so connections survive a new phone.
- To turn it off: in the app, Settings › Data Management › iCloud backup. To delete it: iPhone Settings › [your name] › iCloud › Manage Account Storage › MedTime.

### 2.2 Family Sharing (optional)

You can keep an eye on a loved one's medicines from your own phone. Sharing starts only with **an explicit action on both sides**: the person who will follow sends an invite link; the person being followed sees on their own phone what will be shared and **taps "Accept".**

- **Shared:** the medicine card details of the shared profile (such as name, active ingredient, dose, times, instructions and medicine note), doses taken or undone and when they were marked, the profile name and color, the device's time zone.
- **Not shared:** the Medication Diary (feelings/side-effect notes), blood pressure and glucose readings, photos, leaflets, other profiles.
- The data is transferred via Apple iCloud (CloudKit sharing) and stored **in the follower's iCloud account**; medicine names and details are in end-to-end encrypted fields. If a dose isn't marked within the chosen time, the follower gets an alert; this is calculated on the follower's device.
- **The developer cannot access this data**; it never passes through the developer's servers.
- **To stop:** the person being followed can stop anytime from Settings › Family ("… sees your doses"), and the follower from "Stop following" on the person's screen. When following stops, the shared data is deleted from the follower's iCloud account.
- Accepting an invite is free; following is a Premium feature (with Apple Family Sharing, one family member's subscription is enough).

---

## 3. Permissions

### 3.1 Notifications
Notification permission is requested for medication reminders. Notifications are scheduled **locally on your device**; no server connection involved.

### 3.2 Camera
Camera access is requested only on the *"Add Medication"* screen, to scan barcodes/QR codes on medication boxes or to take photos of medication. Camera footage is not sent to a server.

### 3.3 Photos
Optional photo library access is requested if you want to add medication or profile photos. Selected photos are copied only to the app's internal folder on your device.

### 3.4 Medication Database Lookup
When you scan a barcode/QR code on a medication box or search for a medicine by name, only that **barcode/product code or the medicine name** is sent to an official medication-database service to retrieve the medicine's name and details (leaflet, package, expiry date, etc.). The service used depends on your device region: **NosyAPI** (Turkey), the **U.S. FDA openFDA** database (United States), or **AEMPS CIMA** (Spain). No personal information (your name, profile data, health data, photos, or camera footage) is included in this query — only the scanned code or the search term is transmitted. This feature is optional; if you do not use it, no data is sent.

You can revoke permissions anytime via iOS *Settings &gt; MedTime*.

### 3.5 Apple Health (HealthKit) — Optional Sync
Premium users can optionally turn on *Settings → Apple Health* sync. When on: (1) the **blood pressure, blood glucose and heart rate** measurements you enter in the app and the **insulin doses** you mark are **written** to Apple Health; (2) **blood pressure, blood glucose and heart rate** measurements that your monitor, glucose meter or other apps write to Apple Health are **read** into your measurement log in the app. This feature is **entirely optional** and **off by default**.

- Read and write permissions are approved **separately** and explicitly through the iOS permission sheet; only the data types listed above are accessed (medication lists, steps, sleep etc. are **not read**).
- Only measurements belonging to **your own profile** are written; family member profiles are never synced.
- Data goes directly into the Health store on your device; **nothing is sent to any server**. Your Health data is encrypted by Apple.
- If you delete or edit a measurement in the app, its copy written to Health is updated/removed accordingly.
- You can revoke access anytime via iOS *Settings → Health → Data Access & Devices → İlaçVakti*.
- Health data is never used for advertising, marketing or analytics (compliant with App Store Guideline 5.1.3).

### 3.6 Microphone and Speech Recognition — Optional
Tapping the microphone icon on the measurement screen lets you enter your blood pressure or blood sugar **by speaking**. This feature is **entirely optional**; the microphone is never activated unless you tap that icon.

- Your speech is transcribed **on your device**; the app **requires** iOS on-device speech recognition. **No audio is sent to any server** — the feature works in airplane mode.
- **No audio recording is kept.** Once your speech is transcribed, the audio is not stored; only the recognised numbers are written into the on-screen fields.
- The recognised value is **not saved directly**: it is written into the field and is not recorded until you review it and tap **Save**.
- The microphone is active only on this screen and only when you start it; there is no background listening.
- You can revoke the permission at any time via iOS *Settings &gt; MedTime*.

---

## 4. Crash Reports (Sentry)

To improve app stability, anonymous crash reports are collected via the **Sentry** service.

**Collected:**
- Crash timestamp, device model, iOS version, app version
- Error message and technical stack trace
- Pre-crash technical context (e.g. screens opened)

**Not collected:**
- Username, email, IP address (`sendDefaultPii` disabled)
- Screenshots, personal medication data, health data
- Photos or report contents

Sentry data is used solely for app improvement; **never** for marketing or advertising. Sentry data is retained for up to **90 days**.

Sentry privacy policy: <https://sentry.io/privacy/>

---

## 5. Premium Subscription and RevenueCat

MedTime offers an optional **Premium subscription**:

| Plan | Price | Features |
|---|---|---|
| Monthly | $3.99 | Auto-renews |
| Yearly | $29.99 | Includes **7-day free trial**, auto-renews |
| Lifetime | $49.99 | **One-time payment** — not a subscription, never renews |

> The amounts above are United States App Store prices (for example, £3.99 / £24.99 / £39.99 in the United Kingdom). **Prices vary by country**; the App Store shows the exact amount in your local currency before you complete a purchase.

### Subscription Management
- Subscriptions auto-renew; payment is charged to your iTunes account if not cancelled at least **24 hours** before the end of the current period.
- Cancel: iOS *Settings → Apple ID → Subscriptions*.
- **Family Sharing** is enabled — one subscription can be shared with up to 5 family members.
- Payments are processed by Apple; MedTime has no access to card information.

### Lifetime Free Access for Earlier Users
Users who installed version **2.0.1 (build 5) or earlier** automatically receive **lifetime free Premium** access. This is verified anonymously on-device using the `originalApplicationVersion` field on the Apple receipt.

### RevenueCat (Subscription Validation)
The **RevenueCat** service is used to validate subscription state. An anonymous identifier (App User ID) derived from your Apple ID and Apple receipt data are sent to RevenueCat. Your name, email, or contact information is **not shared**.

RevenueCat privacy policy: <https://www.revenuecat.com/privacy/>

### Advertising Measurement (Apple Search Ads)
MedTime occasionally runs ads on the App Store. To measure which ad brought you to the app, an *attribution token* generated by Apple **at install time** is passed to RevenueCat, which asks Apple whether the install came from an ad.

- The token is **not your advertising identifier (IDFA)** and does not identify you or your device. For this reason no iOS *App Tracking Transparency* prompt is shown — no cross-app tracking takes place.
- Apple returns **campaign-level information only**. It is **never linked** to your name, profile, medications or health data.
- It runs **once, at install**; your use of the app is not tracked for advertising afterwards.
- The sole purpose is to verify that the advertising budget is spent well; it is **not** used to target ads at you or to sell data.

### Terms of Use
Apple Standard EULA applies: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Data Sharing

MedTime does **not share user data with any third party, does not sell it, and does not use it for marketing purposes**. The only exceptions are:

- The medication-database lookups described in Section 3.4 (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) — only the scanned code or searched medicine name is transmitted; it contains no personal data.
- Anonymous crash reports described in Section 4 (Sentry).
- Anonymous subscription validation data and the non-identifying ad attribution token described in Section 5 (RevenueCat + Apple).
- Family sharing described in Section 2.2, **started and approved by you** — only with the person you invited or whose invite you accepted, via Apple iCloud.

---

## 7. Your Rights Under GDPR (EU Users)

If you reside in the EU, under the General Data Protection Regulation (GDPR) you have the rights to **access, correct, delete, object to processing, and data portability**. Our legal bases are: necessity for service provision (Article 6(1)(b)) and legitimate interest for error reporting (Article 6(1)(f)).

---

## 8. Your Rights Under Turkish KVKK

Under Turkish Personal Data Protection Law (KVKK) Article 11, you have rights including: learning whether your data is processed, requesting information, requesting correction or deletion, knowing third parties to whom data was transferred, objecting to automated processing results, and claiming compensation. To exercise these rights, contact <ilacvaktidestek@gmail.com>. Requests are responded to within **30 days**.

---

## 9. Children's Privacy

The app is rated **4+**. Data is not knowingly collected from children under 13. If a parent uses the app to add a child profile (family member), the profile data remains stored locally on the device only.

---

## 10. Data Security

Because your data is mostly stored on your device, it is protected by iOS hardware encryption (Secure Enclave). Communication with third-party services is encrypted over HTTPS. Medicine data in iCloud backup and family sharing is stored in Apple CloudKit's end-to-end encrypted fields; no one, including the developer, can read it.

---

## 11. Changes to This Policy

We may update this policy from time to time. Significant changes will be announced via in-app notification or release notes. Please review the *Last updated* date regularly.

---

## 12. Contact

Email: <ilacvaktidestek@gmail.com>
