# Privacy Policy

**Effective date:** July 1, 2026

This Privacy Policy describes how **GPS Speedometer: Speed Tracker** ("the App", "we", "us") collects, uses, and protects information when you use the App. The App is developed by **Cihat Akyol**.

By installing and using the App, you agree to the practices described in this Privacy Policy.

---

## 1. Information We Collect

### 1.1 Location Data

The App uses your device's GPS (via Google Play Services Location / FusedLocationProvider) to measure your real-time speed. In order to do this, we access:

- **Precise GPS location** (latitude and longitude)
- **GPS-derived speed** (Doppler speed)
- **GPS accuracy** (positional uncertainty)
- **Timestamps** for each speed sample

This data is used to display your current speed, calculate distance, average speed, maximum speed, and to record trip/session history.

### 1.2 Session and Trip Data

When you record a session, the App stores:

- Start and end time
- Duration
- Maximum and average speed
- Total distance traveled
- Speed samples over time (including location coordinates)
- Acceleration benchmark results (e.g., 0–100 km/h time)

### 1.3 Preferences and Settings

The App stores your preferences, including:

- Speed unit (km/h, mph, m/s)
- GPS update interval
- Speed smoothing level
- Theme (light/dark/system)
- Keep-screen-on preference
- Onboarding completion status

### 1.4 Data We Do NOT Collect

We do **not** collect, transmit, or store:

- Your name, email, or any personal identification information (no account system)
- Data on any external server operated by the developer
- Analytics or telemetry data
- Crash reporting data

---

## 2. How Data Is Stored

### 2.1 Local Storage

All data described in Section 1 is stored **entirely on your device**:

- **Session and speed data** is stored in a local on-device database (Room / SQLite).
- **Preferences** are stored in Android DataStore (on-device).
- **CSV export files** are written to the App's private cache directory and shared only when you explicitly choose to export a session.

The App does **not** upload your data to any server operated by the developer. There is no cloud sync, no account system, and no sign-up required.

### 2.2 Device Backup

The App has Android auto-backup enabled. As part of your device's standard backup process, app data may be backed up to your personal Google Drive account. This backup is managed by Android and Google, not by the App. You can control device backups through your Android system settings.

---

## 3. Third-Party Services

The App uses the following third-party services, each with its own privacy practices:

### 3.1 Google Mobile Ads (AdMob)

The App uses the Google Mobile Ads SDK to display banner and interstitial advertisements. When ads are loaded, **Google may automatically collect and transmit** certain data to its servers, including but not limited to:

- Device model and operating system version
- IP address
- Advertising ID (used for ad personalization)
- Coarse location (in some cases)
- Other identifiers and information Google uses for ad delivery and fraud prevention

This data is processed by Google under its own privacy policy, not by the App. You can:

- Reset your advertising ID in Android **Settings > Google > Ads**.
- Opt out of personalized ads via **Settings > Google > Ads > Opt out of Ads Personalization**.

**Google's privacy policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

**How Google uses info from sites or apps that use our services:** [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)

### 3.2 Google Play Services Location

The App uses Google Play Services Location (FusedLocationProvider) to obtain GPS data. Google may use Wi-Fi and cell tower information to assist in determining your location. Your location data is processed locally by the App and is not sent to the developer.

**Google Play Services privacy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 3.3 Google Play In-App Review

The App uses the Google Play In-App Review API to prompt you to rate the App on Google Play. The review flow is handled by Google and is subject to Google's privacy policy.

### 3.4 No Other Third-Party Services

The App does **not** use Firebase, Google Analytics for Firebase, Crashlytics, Amplitude, Mixpanel, Sentry, Facebook SDK, or any other analytics, crash-reporting, or tracking SDK.

---

## 4. How Data Is Used

Your data is used solely to provide the App's functionality:

- **Real-time speed display** from GPS data
- **Session recording** (start, pause, resume, stop)
- **Trip history** (list of past sessions)
- **Session details** (speed chart, stats)
- **Acceleration benchmarks** (e.g., 0–100 km/h)
- **CSV export** when you explicitly request it
- **Restoring an active session** if the App is reopened during a recording

Your data is **not** used for profiling, sold to third parties, or shared for advertising purposes by the developer.

---

## 5. Data Retention

- Your session and speed data is retained on your device **until you delete it**.
- You can delete individual sessions or all history at any time from within the App.
- **Uninstalling the App** removes all locally stored data.

---

## 6. Your Rights and Choices

You have the following rights and controls:

- **Access your data**: All data is available within the App (trip history, session details).
- **Export your data**: Use the CSV export feature for any session.
- **Delete your data**: Delete individual sessions or clear all history from Settings.
- **Revoke location permission**: Go to Android **Settings > Apps > GPS Speedometer > Permissions** and revoke location access. The App cannot measure speed without this permission.
- **Reset advertising ID**: Go to Android **Settings > Google > Ads > Reset advertising ID**.
- **Opt out of personalized ads**: Go to Android **Settings > Google > Ads > Opt out of Ads Personalization**.
- **Disable device backup**: Go to Android system settings to manage device backup preferences.

---

## 7. Children's Privacy

The App is not directed at children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us so we can take appropriate action. Since the App stores all data locally and does not require an account, no parental verification is needed — simply uninstall the App to remove all data.

---

## 8. Data Security

All data is stored locally on your device. The App does not transmit your personal data to any server operated by the developer. The security of your data depends on the security of your device (screen lock, encryption, etc.). We rely on Android's built-in security features to protect locally stored data.

---

## 9. Permissions Used

| Permission | Purpose |
|---|---|
| `ACCESS_FINE_LOCATION` | Precise GPS for speed measurement |
| `ACCESS_COARSE_LOCATION` | Approximate location fallback |
| `INTERNET` *(merged by Ads SDK)* | Required by Google Mobile Ads to load ads |
| `ACCESS_NETWORK_STATE` *(merged by Ads SDK)* | Used by Google Mobile Ads to check network connectivity |
| `AD_ID` *(merged by Ads SDK)* | Used by Google Mobile Ads for advertising ID access |

No other permissions are requested.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Effective date" at the top of this page. We encourage you to review this Privacy Policy periodically to stay informed about how we protect your information.

Material changes will be reflected in the App's store listing or in-app notification where appropriate.

---

## 11. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact:

**Cihat Akyol**
Email: [cihatakyol@gmail.com](mailto:cihatakyol@gmail.com)
