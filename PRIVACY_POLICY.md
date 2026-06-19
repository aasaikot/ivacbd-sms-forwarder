# Privacy Policy for IVACBD SMS Forwarder

**Last Updated:** June 19, 2026

---

## 1. Introduction

Welcome to **IVACBD SMS Forwarder** ("we", "our", or "us"). We respect your privacy and are committed to protecting your personal data. This privacy policy explains how we collect, use, and safeguard your information when you use our Android application.

By using the IVACBD SMS Forwarder app, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Collect

### 2.1 SMS Messages
We collect SMS messages **only from specific senders**: `IVAC_BD`, `IVACBD`, `01708404440`, `IVAC FEES`, and `IVAC`. These messages are automatically forwarded to our Firebase Realtime Database.

### 2.2 Device Information
- **SIM Slot Information**: We detect which SIM card (SIM1 or SIM2) received the SMS for proper identification.
- **Device Model**: We collect your device model name for data organization.

### 2.3 User-Provided Information
- **SIM Numbers**: You can manually enter your SIM numbers through the app interface. This data is stored **locally** on your device only.

### 2.4 We DO NOT Collect
- ❌ SMS messages from any sender other than IVAC
- ❌ Contact list
- ❌ Call logs
- ❌ Location data
- ❌ Photos or media files
- ❌ Any personal information beyond what is stated above

---

## 3. How We Use Your Information

| Data Type | Purpose |
|-----------|---------|
| SMS from IVAC | Forward to Firebase for real-time monitoring |
| SIM Slot | Identify which SIM received the message |
| Device Model | Organize data on the dashboard |
| User SIM Numbers | Identify receiver number on Firebase |

---

## 4. Data Storage and Security

### 4.1 Where Data is Stored
- **Firebase Realtime Database**: All forwarded SMS messages are stored securely in Google's Firebase cloud.
- **Local Storage**: User-entered SIM numbers are stored locally using Android SharedPreferences.

### 4.2 Security Measures
- All data transmission uses HTTPS encryption
- Firebase implements industry-standard security protocols
- Access to Firebase is restricted to authorized users only

### 4.3 Data Retention
- SMS data is retained in Firebase until manually deleted
- Local storage data remains until app is uninstalled or data is cleared

---

## 5. Data Sharing

### 5.1 Third-Party Services
We use **Firebase** (Google) as our cloud database provider. They may process your data in accordance with Google's privacy policy:
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.2 We DO NOT
- ❌ Sell your data
- ❌ Share your data with advertisers
- ❌ Share your data with any third party (except Firebase for storage)
- ❌ Use your data for marketing purposes

---

## 6. Permissions Explained

| Permission | Why We Need It |
|------------|----------------|
| `RECEIVE_SMS` | To detect incoming SMS from IVAC senders |
| `READ_SMS` | To read the content of IVAC SMS messages |
| `READ_PHONE_STATE` | To detect which SIM card received the SMS |
| `POST_NOTIFICATIONS` | To show notification that background service is running |
| `FOREGROUND_SERVICE` | To run the SMS listener in the background |
| `RECEIVE_BOOT_COMPLETED` | To restart the service when device boots |

---

## 7. Your Rights

You have the right to:

- ✅ **Access**: Request a copy of your data
- ✅ **Rectify**: Correct any inaccurate data
- ✅ **Delete**: Request deletion of your data
- ✅ **Withdraw Consent**: Uninstall the app at any time

### How to Exercise Your Rights
Contact us at: **your-email@example.com**

---

## 8. Children's Privacy

This app does not knowingly collect personal information from children under 13. If you believe we have collected such information, please contact us immediately.

---

## 9. Changes to This Privacy Policy

We may update this privacy policy from time to time. We will notify you of any changes by:
- Posting the new policy on this page
- Updating the "Last Updated" date

---

## 10. Contact Us

If you have any questions about this privacy policy, please contact us:

📧 **Email:** your-email@example.com  
🌐 **Website:** https://your-website-url.com  
📱 **GitHub:** https://github.com/yourusername/ivacbd-sms-forwarder

---

## 11. Consent

By using the IVACBD SMS Forwarder app, you consent to this privacy policy.

---

**Last Updated:** June 19, 2026
