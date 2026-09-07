# PRIVACY POLICY - APP LOCK

**Effective Date:** September 7, 2026

### 1. Introduction
Welcome to AppLock. We are committed to protecting your privacy and ensuring your mobile experience remains secure. This Privacy Policy explains how AppLock handles data and permissions.

### 2. Developer Information
**Developer:** SK Software  
**Support:** sk.blink.help@gmail.com  
**Copyright:** © 2026 SK Software

### 3. What AppLock Does
AppLock is a security utility that allows you to protect specific applications on your device using a PIN or Biometric (Fingerprint/Face) authentication. It prevents unauthorized access to your private apps by showing a lock screen overlay when a protected app is opened.

### 4. Information/Data Access
AppLock is designed to be a strictly OFFLINE application for its core security features. We do not collect or transmit your PIN, app protection rules, or biometric data to external servers.

However, to keep the app free, we display advertisements provided by Google AdMob. These advertising services may process certain device-related information as described in the 'Third-Party Services' section below.

### 5. App Permissions
To provide its core functionality and monetize through ads, AppLock requires the following permissions:

*   **Accessibility Service:** Used exclusively to detect when a protected application is brought to the foreground. We do NOT read screen content, keystrokes, or messages.
*   **Usage Stats:** Used as a secondary method to verify app foreground status.
*   **Query All Packages:** Used to display a list of your installed apps.
*   **Biometric/Fingerprint:** Used to allow you to unlock apps using your device's secure hardware.
*   **Internet & Network State:** Required to download and display advertisements from Google AdMob.

### 6. Accessibility Service Usage
AppLock uses Android's AccessibilityService API with strict limitations. It only monitors 'Window State Changed' events to identify the package name of the active app. The 'canRetrieveWindowContent' setting is set to FALSE, meaning the app has no access to your private data, passwords, or chats.

### 7. Biometric Authentication
Biometric data (fingerprints/face templates) is handled entirely by the Android operating system. AppLock never accesses, stores, or transmits your actual biometric data.

### 8. Local Storage & Security
All data created by AppLock is stored locally on your device:
*   Your PIN is stored as a cryptographically salted hash (PBKDF2).
*   Your list of protected apps is stored in a local database.
*   Recent unlock logs are stored locally and are never shared.

All local data is deleted if you uninstall the app or use the 'Reset All Data' option in Settings.

### 9. Data Transmission
Your security data (PIN, protected apps) NEVER leaves your device. The only data transmitted externally is related to advertising (see Section 10).

### 10. Third-Party Services (Google AdMob)
We use Google AdMob for advertising. Google may collect and use certain data (such as advertising IDs, IP addresses, and device identifiers) to show personalized or non-personalized ads, prevent fraud, and measure ad performance. 

For more information on how Google handles your data, please visit: https://policies.google.com/technologies/ads

### 11. Children's Privacy
AppLock does not knowingly collect information from children under 13. The advertising SDK may use identifiers as permitted by law and Google's COPPA-compliant settings.

### 12. Data Deletion
You can delete all locally stored data at any time through the 'Reset All Data' button in the app settings. For third-party advertising data, you can manage your advertising ID settings in your Android device's Google settings.

### 13. Contact Information
If you have any questions about this Privacy Policy, please contact us at: sk.blink.help@gmail.com
