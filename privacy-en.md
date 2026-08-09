---
layout: default
title: Privacy Policy
permalink: /privacy-en/
---

# MedTime (İlaçVakti) — Privacy Policy

**Last updated:** August 2, 2026

MedTime (İlaçVakti) is a mobile application developed by Pharmacist **Mehmet Tuğberk Özsoy**, designed to help users track their medications. Your privacy is our top priority; this policy transparently explains what data is processed and how.

Turkish version: [privacy-tr](/ilacvakti-legal/privacy-tr/)

---

## 1. Data Not Collected

MedTime does **not** collect personal identifiers (name, email, phone, ID number, date of birth, etc.) from users, does not send them to our servers, and does not share them with third parties. No account creation is required; the app works entirely **anonymously**.

Detailed list of data not collected:
- ❌ Advertising or analytics tracking
- ❌ Third-party analytics services (Google Analytics, Facebook Pixel, etc.)
- ❌ Location data
- ❌ Contacts, calendar
- ❌ Storing audio recordings (the microphone is only activated for optional voice entry, see 3.6)
- ❌ Account creation, email, phone
- ❌ Apple Health data is **never read** (for the optional write-only sync, see 3.5)

---

## 2. Local Storage (Data Kept on Your Device)

All information you enter is stored **only on your device's internal memory**:

- Medication names, dosages, reminder times
- Profile names (names you provide) and optional profile photo
- Medication stock information and photos
- Treatment history, taken/skipped logs
- Streak and badge data
- Manually added health reports and notes
- Theme, language, notification sound, and settings preferences

When you delete the app, all this data is deleted with your device.

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

### 3.5 Apple Health (HealthKit) — Optional Write-Only Sync
Premium users can optionally enable *Settings → Save to Apple Health* so that the **blood pressure, blood glucose and heart rate** measurements they enter in the app are **also written** to the Apple Health app. This feature is **entirely optional** and **off by default**.

- İlaçVakti **never reads** your Health data; access is **write-only** and explicitly approved through the iOS permission sheet.
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
| Monthly | approx. $0.99 | Auto-renews |
| Yearly | approx. $5.99 | Includes **7-day free trial**, auto-renews |

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

### Terms of Use
Apple Standard EULA applies: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Data Sharing

MedTime does **not share user data with any third party, does not sell it, and does not use it for marketing purposes**. The only exceptions are:

- The medication-database lookups described in Section 3.4 (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) — only the scanned code or searched medicine name is transmitted; it contains no personal data.
- Anonymous crash reports described in Section 4 (Sentry).
- Anonymous subscription validation data described in Section 5 (RevenueCat + Apple).

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

Because your data is mostly stored on your device, it is protected by iOS hardware encryption (Secure Enclave). Communication with third-party services is encrypted over HTTPS.

---

## 11. Changes to This Policy

We may update this policy from time to time. Significant changes will be announced via in-app notification or release notes. Please review the *Last updated* date regularly.

---

## 12. Contact

Email: <ilacvaktidestek@gmail.com>
