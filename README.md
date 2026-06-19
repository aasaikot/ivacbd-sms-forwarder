# 📱 IVACBD SMS Forwarder

[![Version](https://img.shields.io/badge/version-1.0-green.svg)](https://github.com/yourusername/ivacbd-sms-forwarder)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)](https://developer.android.com)

## 📖 Overview

**IVACBD SMS Forwarder** is a specialized Android application designed to automatically detect, filter, and forward SMS messages from **IVAC (IVAC_BD, IVACBD, 01708404440)** to Firebase Realtime Database in real-time. The app runs silently in the background, ensuring you never miss important IVAC notifications.

---

## ✨ Key Features

### 📨 **Smart SMS Detection**
- Automatically detects SMS from IVAC senders
- Supports multiple sender IDs: `IVAC_BD`, `IVACBD`, `01708404440`, `IVAC FEES`, `IVAC`
- Real-time processing with duplicate message prevention

### 🔄 **Multi-SIM Support**
- Detects which SIM card received the SMS (SIM1 or SIM2)
- Allows manual SIM number configuration for accurate identification
- Perfect for users with dual-SIM devices

### ☁️ **Firebase Integration**
- Seamless data upload to Firebase Realtime Database
- Real-time synchronization with web dashboard
- Secure data storage with server timestamps

### 📊 **Real-time Monitoring**
- Web dashboard with live message viewing
- Auto-refresh every second for instant updates
- Modern Glass + Hacking theme UI
- Mobile-responsive design

### 🔐 **Privacy & Security**
- Only forwards messages from specific IVAC senders
- No data sharing with third parties
- All data stored securely in Firebase
- User-controlled SIM number configuration

---

## 📸 Screenshots

| Home Screen | Settings | Web Dashboard |
|-------------|----------|---------------|
| ![Home](screenshots/home.png) | ![Settings](screenshots/settings.png) | ![Dashboard](screenshots/dashboard.png) |

---

## 🏗️ Architecture
