# 📡 Speedo

A minimalist, high-visibility digital speedometer designed explicitly for Android mobile devices and vehicle dashboard mounts. 

Live Web App Link: **[sol-lee-soft.github.io/speedo](https://sol-lee-soft.github.io/speedo/)**

---

## 🚀 Features

* **High-Contrast Interface:** Deep black background designed to save battery on OLED screens and eliminate night-driving glare.
* **Auto-Scaling Layout:** Uses responsive browser view metrics (`vmin`) to keep the velocity readout as large as possible on any screen size.
* **Dual-Orientation UI:** * **Portrait Mode:** Displays speed alongside auxiliary live telemetry (Altitude in feet, Compass Cardinal Direction). Tap for full screen.
  * **Landscape Mode:** Automatically hides the bottom telemetry panel to provide a massive, distraction-free fullscreen speed layout when the screen is tapped.
* **Hardware GPS Integration:** Taps directly into raw satellite data feeds with zero caching to ensure accurate velocity tracking. Altitude may have a margin of error and compass may take time and motion to update.

---

## 📲 Installation on Android (PWA Wrapper)

You don't need to download anything from the Google Play Store. You can pin this directly to your phone as a standalone app:

1. Open **Google Chrome** on your Android device.
2. Navigate to: `https://sol-lee-soft.github.io/speedo/`
3. Tap the **three dots menu icon** in the top right corner of Chrome.
4. Select **"Add to Home screen"**.

The app will install an icon onto your launcher. When opened from the home screen, it hides the browser address bar entirely, behaving exactly like a native Android application.

---

## 🔒 Privacy & Data Behavior

* **Local Computation:** All geolocation mapping, unit conversions, and coordinates are calculated in real-time directly on your device's browser engine.
* **Zero Telemetry Logging:** No coordinates, trip histories, or location metrics are ever tracked, saved, or transmitted to external servers.
