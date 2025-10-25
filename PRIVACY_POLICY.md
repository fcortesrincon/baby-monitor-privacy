# Privacy Policy for Baby Monitor Sound

**Last Updated:** October 25, 2024

**Effective Date:** October 25, 2024

---

## 1. Introduction

Baby Monitor Sound ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application ("App") collects, uses, and safeguards your information.

**Developer:** Felipe Cortes Rincon
**Contact Email:** babymonitorsound@gmail.com
**App Package:** com.fcortesrincon.babymonitorsound

By using Baby Monitor Sound, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Collect

### 2.1 Audio Data (Microphone Access)
- **What we collect:** Real-time audio from your device's microphone when operating in Emisor (transmitter) mode
- **How we use it:** Audio is transmitted in real-time to connected receptor devices via peer-to-peer WebRTC connection
- **Storage:** We do NOT store, record, or retain any audio data. Audio is only transmitted live and is never saved to any server or cloud storage
- **Third-party access:** Audio data is NOT shared with any third parties

### 2.2 Device Information
- **What we collect:**
  - Battery level and charging status
  - Device type and model
  - Network connectivity status
- **How we use it:** To display battery status and ensure proper connection between devices
- **Storage:** Stored locally on your device only
- **Third-party access:** NOT shared with third parties

### 2.3 Network Information
- **What we collect:** Local IP addresses for WebRTC peer-to-peer connections
- **How we use it:** To establish direct audio connections between emisor and receptor devices
- **Storage:** Used temporarily during active connections only
- **Third-party access:** NOT shared with third parties (direct peer-to-peer connection)

### 2.4 Push Notification Tokens
- **What we collect:** Firebase Cloud Messaging (FCM) tokens
- **How we use it:** To send push notifications when baby cry is detected and receptor is in background
- **Storage:** Stored by Firebase (Google) according to their privacy policy
- **Third-party access:** Firebase/Google only, for notification delivery

### 2.5 Camera Access (QR Code Scanning)
- **What we collect:** Camera access for QR code scanning (receptor mode only)
- **How we use it:** To scan QR codes for easy connection to emisor device
- **Storage:** No images or camera data is stored. Camera is only used for real-time QR code detection
- **Third-party access:** NOT shared with third parties

### 2.6 App Settings and Preferences
- **What we collect:**
  - Baby name
  - Cry detection settings (threshold, duration, cooldown)
  - Connection history (IP addresses, baby names)
  - Audio output preferences
- **How we use it:** To provide personalized experience and quick reconnection
- **Storage:** Stored locally on your device using SharedPreferences
- **Third-party access:** NOT shared with third parties

---

## 3. How We Use Your Information

We use the collected information for the following purposes:

1. **Core Functionality:** Enable real-time baby monitoring with audio streaming
2. **Cry Detection:** Analyze audio levels to detect baby crying and send alerts
3. **Push Notifications:** Notify receptor users when baby is crying
4. **Connection Management:** Facilitate easy connection between emisor and receptor devices
5. **User Experience:** Remember settings and preferences
6. **Battery Monitoring:** Display battery status to prevent unexpected disconnections

---

## 4. Data Storage and Retention

### 4.1 Local Storage Only
- All app settings, preferences, and connection history are stored **locally on your device**
- We do NOT use cloud storage for any user data
- Audio is NEVER stored anywhere (real-time transmission only)

### 4.2 Data Retention
- **Audio Data:** NOT retained (0 seconds - live streaming only)
- **App Settings:** Retained until you uninstall the app or clear app data
- **Connection History:** Retained until you manually delete or clear app data
- **FCM Tokens:** Retained by Firebase while app is installed

### 4.3 Data Deletion
- **Uninstall the app:** All local data is automatically deleted
- **Clear app data:** Settings → Apps → Baby Monitor Sound → Clear Data
- **Manual deletion:** Use in-app options to delete connection history

---

## 5. Third-Party Services

We use the following third-party services:

### 5.1 Firebase Cloud Messaging (Google)
- **Purpose:** Push notifications for baby cry alerts
- **Data shared:** FCM device tokens, basic app usage
- **Privacy Policy:** https://firebase.google.com/support/privacy
- **Data location:** Google servers (various locations)

### 5.2 WebRTC (Peer-to-Peer)
- **Purpose:** Real-time audio streaming
- **Data shared:** Audio stream between your devices only (direct connection)
- **Privacy:** No third-party servers involved in audio transmission
- **Data location:** Your local network only

---

## 6. Data Sharing and Disclosure

### 6.1 We Do NOT Share Your Data
- We do NOT sell your personal information
- We do NOT share your data with third parties for marketing purposes
- We do NOT use your data for advertising
- We do NOT track your behavior

### 6.2 Legal Requirements
We may disclose your information only if required by law, such as:
- In response to a valid legal request (court order, subpoena)
- To protect our rights or safety
- To comply with applicable laws and regulations

---

## 7. Children's Privacy

Baby Monitor Sound is designed for **parents and caregivers** (adults 18+) to monitor babies and young children. The app is NOT directed at children under 13.

- We do NOT knowingly collect information from children under 13
- If you believe a child has provided us with personal information, please contact us
- The app is used BY adults to monitor children, not FOR children to use

**COPPA Compliance:** This app is not subject to COPPA as it is not directed at children.

---

## 8. Security

We take reasonable measures to protect your information:

- **Encryption in Transit:** All audio and data transmissions use secure WebRTC connections
- **No Cloud Storage:** Reduces risk by not storing sensitive data remotely
- **Local Storage Only:** Data remains on your device under your control
- **Signed App:** Release version is cryptographically signed

However, no method of transmission over the internet or electronic storage is 100% secure. We cannot guarantee absolute security.

---

## 9. Your Rights (GDPR Compliance)

If you are in the European Economic Area (EEA), you have the following rights:

1. **Right to Access:** Request a copy of your data (contact us)
2. **Right to Deletion:** Request deletion of your data (uninstall app or contact us)
3. **Right to Correction:** Request correction of inaccurate data
4. **Right to Portability:** Request transfer of your data
5. **Right to Withdraw Consent:** Stop using the app at any time
6. **Right to Object:** Object to processing of your data

**How to exercise rights:** Email us at [YOUR_EMAIL_HERE] or uninstall the app.

---

## 10. California Privacy Rights (CCPA)

If you are a California resident, you have the right to:

1. **Know:** What personal information is collected
2. **Delete:** Request deletion of your personal information
3. **Opt-Out:** We do NOT sell your information (nothing to opt-out of)
4. **Non-Discrimination:** We will not discriminate for exercising your rights

**How to exercise rights:** Email us at [YOUR_EMAIL_HERE]

---

## 11. International Data Transfers

- Audio data: NOT transferred (stays on local network)
- FCM tokens: May be transferred to Google servers globally
- No other data is transferred internationally

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last Updated" date.

**How you'll be notified:**
- Updated date at the top of this policy
- In-app notification (for major changes)
- Continued use of the app after changes constitutes acceptance

---

## 13. Permissions Explained

The app requests the following permissions:

| Permission | Purpose | Required |
|------------|---------|----------|
| **RECORD_AUDIO** | Capture baby's audio for monitoring | Yes (Emisor) |
| **CAMERA** | Scan QR codes for easy connection | Yes (Receptor QR feature) |
| **INTERNET** | WebRTC audio streaming and push notifications | Yes |
| **ACCESS_NETWORK_STATE** | Check network connectivity | Yes |
| **ACCESS_WIFI_STATE** | Detect WiFi network for connection | Yes |
| **POST_NOTIFICATIONS** | Send cry detection alerts | Yes |
| **VIBRATE** | Alert notifications with vibration | No |
| **WAKE_LOCK** | Keep device awake during monitoring | Yes |
| **FOREGROUND_SERVICE** | Continue monitoring in background | Yes (Emisor) |

You can revoke permissions at any time in your device settings, but this may limit app functionality.

---

## 14. Data We Do NOT Collect

To be clear, we do NOT collect:

- ❌ Your name, email, or phone number
- ❌ Your location or GPS data
- ❌ Your contacts or address book
- ❌ Your photos or media files
- ❌ Your browsing history
- ❌ Your financial information
- ❌ Any personally identifiable information (PII)
- ❌ Analytics or tracking data

---

## 15. Contact Us

If you have questions about this Privacy Policy or our practices, please contact us:

**Email:** babymonitorsound@gmail.com
**Developer:** Felipe Cortes Rincon
**Location:** Munich, Bavaria, Germany

**Response Time:** We aim to respond within 48 hours.

---

## 16. Consent

By using Baby Monitor Sound, you consent to:
- This Privacy Policy
- Collection and use of information as described
- Use of third-party services (Firebase)

**How to withdraw consent:** Uninstall the app and contact us to delete any remaining data.

---

## Summary

**What we collect:** Audio (live only), device info, battery status, FCM tokens, app settings
**What we DON'T collect:** PII, location, contacts, photos, browsing history
**Storage:** Local device only (except FCM tokens with Firebase)
**Sharing:** We do NOT share or sell your data
**Purpose:** Baby monitoring with real-time audio and cry detection
**Your control:** Uninstall app to delete all data

---

**This Privacy Policy is effective as of October 25, 2024.**

© 2024 Felipe Cortes Rincon. All rights reserved.
