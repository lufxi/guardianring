# 💍 Guardian Ring — Women Safety App

> **Hidden SOS Trigger with Shake & Voice Activation**

![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)
![Language](https://img.shields.io/badge/Language-Java%2FKotlin-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 📖 Overview

**Guardian Ring** is an Android-based personal safety application designed to empower women with discreet, fast emergency alerting. Using **shake detection (accelerometer)** and **voice-activated commands**, the app silently sends an SOS alert with real-time GPS location to pre-selected emergency contacts — all without unlocking the phone or opening the app.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🤝 **Hidden SOS Trigger** | Trigger alerts via shake gesture or voice command |
| 📍 **Real-Time GPS Location** | Automatically shares live location with emergency contacts |
| 📲 **Emergency Contact Alerts** | Sends SMS/notifications to trusted contacts |
| 📞 **Emergency Call** | One-tap direct call to emergency services |
| 🔦 **Flashlight Strobe** | Activates strobe light to attract attention |
| 🔊 **Siren Mode** | Plays a loud alarm to deter threats |
| 📱 **Fake Call** | Simulates an incoming call to escape uncomfortable situations |
| 🛡️ **Safety Tips** | Built-in safety guidance and self-defense tips |
| 🔇 **Silent Background Operation** | Runs in the background with no visible indicators |

---

## 🧠 How It Works
```
User in Danger
     │
     ├── Shakes phone repeatedly  ──►  Accelerometer detects pattern
     │                                         │
     └── Says voice command       ──►  Voice recognition triggers
                                               │
                                    SOS Activated in Background
                                               │
                         ┌─────────────────────┼─────────────────────┐
                         ▼                     ▼                     ▼
                  GPS Location          SMS to Contacts        Emergency Call
```

---

## 🔧 Technical Highlights

- **Sensor-Based Detection** — Accelerometer shake pattern recognition
- **Voice Activation** — Background speech recognition for keyword commands
- **Background Services** — Persistent foreground service keeps app always ready
- **Real-Time GPS** — FusedLocationProvider for accurate, battery-efficient tracking
- **Secure Data Handling** — Emergency contacts stored securely on-device

---

## 🔒 Privacy & Legal

- [Privacy Policy](privacy-policy.html)
- [Terms of Service](terms-of-service.html)

All user data is stored locally on-device and never shared with third parties.

---

<p align="center">Made with ❤️ for women's safety</p>
