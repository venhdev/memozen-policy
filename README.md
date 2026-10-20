# MemoZen Policy & Legal Compliance Hub

Official public repository hosting the Single Source of Truth for legal, terms, and privacy compliance surfaces for the MemoZen mobile application (`com.venhdev.memozen`).

Hosted via GitHub Pages at: [https://venhdev.github.io/memozen-policy/](https://venhdev.github.io/memozen-policy/)

---

## Authoritative Store Declaration Endpoints

When completing store listing metadata, copy and paste the corresponding endpoints below:

| Store Declaration Field | Target Platform | Canonical Production URL |
| :--- | :--- | :--- |
| **Privacy Policy URL** | Google Play Console & App Store Connect | `https://venhdev.github.io/memozen-policy/` |
| **Data Deletion Request URL** | Google Play Console (Data Safety Form) | `https://venhdev.github.io/memozen-policy/#data-deletion` |
| **Terms of Service (EULA)** | App Store Connect & Google Play Console | `https://venhdev.github.io/memozen-policy/#terms` |
| **Support Contact** | Store Listing & In-App Drawer | `support@memozen.io` |

---

## Architectural & Compliance Invariants

1. **Unauthenticated Deletion Intake**: The `#data-deletion` anchor provides a compliant mechanism for uninstalled users to submit deletion requests via verified email dispatch, fulfilling Google Play User Data policies without login walls.
2. **Explicit `SCHEDULE_EXACT_ALARM` Disclosures**: Accurately itemizes exact countdown alarms for focus sessions and mindful reflection reminders on Android 13+ (API 33/34+).
3. **Dual-Platform Permissions Matrix**: Itemizes Android manifests scopes alongside iOS `Info.plist` usage strings (`NSCameraUsageDescription`, `NSMicrophoneUsageDescription`, `NSPhotoLibraryUsageDescription`, `NSLocationWhenInUseUsageDescription`).
4. **Subscription Management Links**: Discloses direct links to Google Play and Apple App Store subscription cancellation surfaces to protect users against accidental auto-renewals.
5. **Bilingual Presentation**: Native instant switching between English (international review compliance) and Tiếng Việt (local community transparency).
