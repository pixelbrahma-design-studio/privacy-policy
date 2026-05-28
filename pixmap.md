# Privacy Policy for PixMap

**Effective date:** 28 May 2026
**Last updated:** 28 May 2026

PixMap ("the App", "we", "us", "our") is provided by **Pixelbrahma Design Studio Private Limited**, registered in India. This Privacy Policy explains what personal data we collect, why we collect it, how we use it, who we share it with, and the choices you have.

By using PixMap you agree to the practices described below. If you do not agree, do not use the App.

---

## 1. What data we collect

We collect only the data the App needs to function. We do **not** sell your personal data and we do **not** use it for advertising.

### 1.1 Data you provide directly
- **Phone number** — used as your account identifier and to sign you in via one-time password (OTP).
- **Display name and profile photo** (optional) — shown alongside places you share or pin.
- **Place titles, notes, and the location coordinates** you save (e.g. "Parking near home", "Friend's house").
- **Photos you attach** to a saved place (taken with your camera or chosen from your photo library).
- **Voice transcripts** when you use Siri ("Save this place in PixMap") or Google Assistant ("Save this place in PixMap"). The transcribed text becomes the place title.

### 1.2 Data collected automatically
- **Precise device location** (GPS) — captured at the moment you save a place, and continuously when you've granted background location permission so the App can alert you when you approach a previously saved place.
- **Crash and performance data** — non-personal diagnostics (stack traces, device model, OS version, App version) collected via Firebase Crashlytics so we can fix bugs.
- **Firebase Cloud Messaging registration token** — a per-device identifier needed to deliver push notifications (e.g. sync confirmations, proximity alerts).
- **Coarse usage timestamps** — when the App is opened, when a place is created or edited — stored alongside that place record.

### 1.3 Optional features
- **Contacts** — if you tap the Friends tab and grant contacts permission, the App reads your address book locally on the device to surface friends who already use PixMap. Contact phone numbers are hashed before being sent to our servers for matching. **The plaintext contents of your address book never leave your device.**
- **Photo library** — accessed only when you tap "Choose photo" on the Save Place screen.
- **Microphone and speech recognition** — used only when you tap a dictation icon on a text field, or invoke Siri/Google Assistant.

We do **not** collect contacts, photos, microphone audio, or location in the background unless you have explicitly granted that permission.

---

## 2. How we use your data

| Purpose | Data used |
|---|---|
| Authenticate you | Phone number, OTP, Firebase Auth tokens |
| Save and retrieve your places | Place titles, coordinates, photos, timestamps |
| Show places near you | Device location (foreground) |
| Notify you when you're near a saved place | Device location (background), FCM token |
| Sync places across your devices | All your place data |
| Find friends among your contacts | Hashed contact phone numbers |
| Diagnose and fix crashes | Crash logs, device model, OS version, App version |
| Provide CarPlay (iOS) and Android Auto experiences | Place data + current location |

We do **not** use your data for profiling, ad targeting, or building predictive user models.

---

## 3. Who we share data with

Your data is stored on our infrastructure and a small set of trusted service providers acting on our behalf:

- **Google Firebase** (Authentication, Firestore Database, Cloud Storage, Cloud Messaging, Crashlytics, Cloud Functions) — Google Ireland Ltd / Google LLC, USA. Firebase is a data processor; data is stored in Google's secure data centres.
- **Google Cloud Translation API** — translates user-entered text between languages when the Dual-Language storage feature is used. Text sent to translation is not retained by Google.
- **Apple Inc.** — handles Siri voice intents and CarPlay scene rendering on iOS. PixMap receives the transcribed text and location from Apple; Apple does not retain copies of your saved places.
- **Google LLC** — handles "Hey Google" App Actions and Android Auto scene rendering. Same arrangement as Apple.

We share data with these processors only to the extent needed for the App to work. We do **not** sell, rent, or trade your personal data to third parties for marketing.

We may disclose data if required by valid legal process (court order, regulatory authority) and only to the minimum extent legally compelled.

---

## 4. Where your data is stored

Data is stored in Google Cloud regions selected for low latency and regulatory compliance. We may transfer data between regions for backup and disaster recovery. By using the App you consent to these transfers, including across international borders.

---

## 5. How long we keep your data

- **Active accounts** — retained for as long as your account is active.
- **Deleted accounts** — when you delete your account from in-app Settings, your places, photos, and friend records are removed from our active database within 30 days. Encrypted backups containing this data may persist for up to 90 days before being permanently overwritten.
- **Crash logs** — retained for up to 90 days, then deleted.
- **Authentication audit logs** — retained for up to 12 months for security investigation.

---

## 6. Your rights

You have the right to:
- **Access** the data we hold about you.
- **Correct** inaccurate data — most fields are directly editable in the App.
- **Delete** your account and associated data — Settings → Delete account.
- **Export** a copy of your data — email us at the address below and we'll provide a JSON export within 30 days.
- **Withdraw consent** — revoke any permission (location, contacts, microphone, photos, notifications) at any time from your device's Settings; revoking a permission may disable the corresponding feature.

If you are in the EU/EEA, UK, or India, you also have the rights granted under GDPR, UK GDPR, and the Digital Personal Data Protection Act 2023 (India) respectively, including the right to lodge a complaint with your data protection authority.

---

## 7. Security

We use industry-standard safeguards:
- All data in transit is encrypted with TLS 1.2+.
- Data at rest in Firebase is encrypted by Google.
- Firestore security rules restrict each user's reads/writes to their own data (places, photos, friend records).
- Phone number authentication is handled entirely by Firebase Auth; we never see your raw OTP code.

No system is perfectly secure. If you become aware of a vulnerability, please email us immediately at the contact address below.

---

## 8. Children's privacy

PixMap is not directed at children under 13. We do not knowingly collect personal data from children under 13. If you believe we have done so, please contact us and we will delete the data promptly.

---

## 9. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top. If the changes are material we will notify you in the App or by email. Continued use of the App after the effective date of a revised Privacy Policy constitutes acceptance of the revised policy.

---

## 10. Contact us

For privacy questions, data requests, or to exercise any right above, contact:

**Pixelbrahma Design Studio Private Limited**
Email: hareesh@pixelbrahma.com

---

*This policy was prepared in good faith. It is not a substitute for legal advice. If you operate PixMap in a regulated jurisdiction, please review with qualified counsel.*
