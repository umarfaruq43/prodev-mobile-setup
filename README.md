# 🧭 Expo Go Setup Guide

## 🚀 Installation Steps

1. **Visit the official Expo Go homepage**  
   👉 [https://expo.dev/go](https://expo.dev/go)

2. **Select the latest SDK version**

    - Ensure your project uses the latest SDK version supported by Expo Go.

3. **Install Expo Go for your device:**

    - **Android:** [Download from Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
    - **iOS:** [Download from Apple App Store](https://apps.apple.com/app/expo-go/id982107779)

4. **Open the Expo Go app** on your mobile device.

5. **Sign in or create a new Expo account**

    - You’ll need this account to run and test your projects.

6. **Connect your device and development environment**
    - Make sure both are on the **same Wi-Fi network**.
    - Run your project using:
        ```bash
        npx expo start
        ```
    - Scan the QR code displayed in the terminal or browser with Expo Go.

---

## 🧩 Challenges Faced

| Challenge            | Description                                  | Solution                                                       |
| -------------------- | -------------------------------------------- | -------------------------------------------------------------- |
| ❌ Connection issues | Couldn’t connect device to local server      | Ensured both phone and computer were on the same Wi-Fi network |
| ⚠️ SDK mismatch      | Project SDK version not supported by Expo Go | Updated SDK version using `npx expo upgrade`                   |
| 🔐 Login errors      | Trouble signing in on Expo Go                | Reinstalled app and cleared cache                              |

---

## 📝 Notes

-   Keep your Expo Go app **updated** for compatibility with the latest SDKs.
-   Use `npx expo doctor` to diagnose and fix common issues.
-   For detailed documentation, visit the official Expo docs: [https://docs.expo.dev](https://docs.expo.dev)
