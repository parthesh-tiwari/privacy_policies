# Privacy Policy — StampIt

**Effective Date:** 26 March 2026
**Last Updated:** 26 March 2026

---

## 1. Overview

StampIt ("the App") is a watermarking application developed and published as a one-time purchase on the Google Play Store and Apple App Store. This Privacy Policy explains what data the App collects, how it is used, and your rights as a user.

We have designed StampIt to work fully offline. We do not require you to create an account to use the App. We do not sell your data. We do not run ads.

---

## 2. Developer Information

**App Name:** StampIt
**Developer:** Navastra Technologies
**Contact Email:** parthti1000@gmail.com
**Website:** 

---

## 3. Data We Collect

### 3.1 Data Collected Locally (On Your Device Only)

StampIt stores the following data locally on your device using SQLite. This data never leaves your device unless you explicitly use the backup/export feature.

| Data | Purpose |
|---|---|
| Display name | Used to auto-fill copyright watermark text |
| Saved watermark templates | Store your custom templates for reuse |
| Stamp job history | Log of your past watermark exports (thumbnails, template used, photo count) |
| App preferences | Dark mode, haptic feedback, export quality, output folder path |

### 3.2 Data Collected via Google Sign-In (Optional)

If you choose to sign in with Google (optional feature on the Profile screen), we receive the following from Google:

| Data | Purpose |
|---|---|
| Display name | Pre-fill display name if not already set |
| Email address | Account identification |
| Profile photo URL | Display in the Profile screen |

Sign-in is entirely optional. All core features of StampIt work without signing in. We do not use your Google account data for any purpose other than displaying it on the Profile screen.

### 3.3 Data We Do NOT Collect

- We do not collect, upload, or store your photos, videos, or PDF files on any server.
- We do not track your usage, behaviour, or analytics.
- We do not collect device identifiers, advertising IDs, or location data.
- We do not share any data with third-party advertisers.

---

## 4. Permissions Used

The App requests the following device permissions:

| Permission | Reason |
|---|---|
| `READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE` | To pick photos and PDFs for watermarking |
| `READ_MEDIA_VIDEO` | To pick videos for watermarking |
| `WRITE_EXTERNAL_STORAGE` (Android ≤ 9) | To save exported files to device storage |
| `INTERNET` | Required for Google Sign-In and Google Fonts loading only |

We do not access any files beyond what you explicitly select through the system file picker or camera roll. No background file access occurs.

---

## 5. Third-Party Services

StampIt integrates the following third-party services:

### 5.1 Google Sign-In & Firebase Authentication
Used for optional user sign-in. Governed by [Google's Privacy Policy](https://policies.google.com/privacy).

### 5.2 Google Fonts
The App loads fonts from the Google Fonts API at runtime for watermark rendering. This involves a network request to Google's servers. Governed by [Google's Privacy Policy](https://policies.google.com/privacy).

### 5.3 Syncfusion Flutter PDF
Used for PDF rendering and export. This is a local library — no data is sent to Syncfusion servers.

We do not integrate any advertising SDKs, analytics SDKs, or crash reporting tools.

---

## 6. Data Storage & Security

All user data (templates, settings, stamp history) is stored locally on your device in a SQLite database managed by the `sqflite` package. Exported watermarked files are saved to your device's local storage or gallery.

We do not operate any servers that receive or store your personal data, with the exception of what Google Firebase Authentication handles if you choose to sign in (governed by Google's policies).

---

## 7. Data Retention

Since all data is stored locally on your device:

- Data persists until you uninstall the App or manually clear its data via your device settings.
- If you sign out of Google Sign-In, your Google account data is removed from the App's memory immediately.
- Uninstalling the App removes all locally stored data.

---

## 8. Children's Privacy

StampIt is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us at [your@email.com] and we will take steps to delete such information.

---

## 9. Your Rights

Depending on your location, you may have the following rights regarding your data:

- **Access:** Request a copy of the data we hold about you.
- **Deletion:** Request deletion of your data. Since data is stored locally, you can delete it directly by clearing the App's data in your device settings or uninstalling the App.
- **Portability:** The App includes a template export feature (JSON) so you can take your templates with you.
- **Withdrawal of consent:** You may sign out of Google Sign-In at any time via the Profile screen.

To exercise any rights related to Google Sign-In data, contact us at parthti1000@gmail.com

---

## 10. In-App Purchases

StampIt is a one-time purchase app. There are no subscriptions. Purchase transactions are processed entirely by the Google Play Store or Apple App Store. We do not receive or store your payment information. Refer to [Google Play's privacy policy](https://policies.google.com/privacy) for purchase-related data handling.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 12. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

**Email:** parthti1000@gmail.com
**Developer:** Navastra Technologies

---

*This privacy policy was written for StampIt, a watermarking app available on the Google Play Store and Apple App Store.*
