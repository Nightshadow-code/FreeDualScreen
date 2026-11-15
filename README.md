# FreeDualScreen

### A free community continuation of the original DualScreen Launcher by ProfMags.

**Community-powered. Completely free. No subscriptions.**

FreeDualScreen is an independent community project based on the original DualScreen Launcher by ProfMags.

Our mission is to keep the dual-screen launcher experience accessible to everyone. We aim to provide a free and open experience without subscriptions, paid unlocks, or unnecessary premium restrictions.

---

## 🎯 Our Goals

- Keep features free and accessible.
- No subscriptions or paid unlocks.
- Improve the dual-screen Android experience.
- Provide regular updates and bug fixes.
- Encourage community contributions.
- Maintain an open and community-driven project.
- Support compatible dual-screen Android devices.

---

## 📥 Downloads

Official APK releases will be published through GitHub Releases.

**[Download FreeDualScreen](https://github.com/Nightshadow-code/FreeDualScreen/releases)**

Only download APK files from the official project releases.

---

## 📱 Compatibility

FreeDualScreen is designed for compatible Android devices with dual-screen functionality.

Compatibility may vary depending on:
- Android version.
- Device manufacturer.
- Hardware configuration.
- System-level dual-screen features.

---

## ⚠️ Known Issues

FreeDualScreen is an independent community project based on the original DualScreen Launcher. Some original integrations may not work exactly as expected.

### Authentication Issues

Some users may experience authentication problems when starting the application.

These issues may be related to services or authentication systems inherited from the original launcher.

We are investigating these issues and will document improvements as they become available.

### Original Launcher Update Signature

FreeDualScreen uses its own APK signing certificate.

The original developer's launcher updates are signed with a different certificate. Android does not allow an application signed with a different certificate to update an existing installation.

As a result:
- Original launcher updates may fail.
- Signature verification errors may appear.
- FreeDualScreen requires its own compatible update process.

Future FreeDualScreen releases will use the project's own signing certificate.

### General Compatibility

Some features may behave differently depending on the Android version and device configuration.

Known issues will be documented and addressed as development continues.

---

## 🔨 Building from Source

### Requirements

- Android Studio
- Java Development Kit (JDK 17)
- Android SDK
- Android SDK Build Tools
- Git

### Clone the Repository

```bash
git clone https://github.com/Nightshadow-code/FreeDualScreen.git
cd FreeDualScreen
```

### Build the Debug APK

```bash
./gradlew :launcher:assembleDebug
```

The generated APK can be found in:

```text
launcher/build/outputs/apk/debug/
```

### APK Signing

Release APKs are signed using the official FreeDualScreen project signing certificate.

The private signing key is kept securely by the project maintainer and must never be committed to the repository.

---

## 🤝 Contributing

Community contributions are welcome!

You can help by:

- Reporting bugs.
- Suggesting new features.
- Testing releases.
- Improving the source code.
- Improving documentation.
- Submitting pull requests.

Every contribution helps improve FreeDualScreen.

---

## 📜 Credits

FreeDualScreen is based on the original DualScreen Launcher by ProfMags.

Original source repository:

https://github.com/JoeCorrell/DualScreen-Launcher-Source

FreeDualScreen is an independent community project and is not an official release of ProfMags.

All original components remain subject to their applicable licensing terms.

---

## 📄 License

Please refer to the [LICENSE](LICENSE) file for the licensing terms applicable to this project.

Original copyright notices and license requirements must be preserved.

---

## 🌍 Project Information

**Project Name:** FreeDualScreen

**Project Type:** Community Continuation

**Platform:** Android

**Development:** Community-driven

**Official Repository:**

https://github.com/Nightshadow-code/FreeDualScreen

**Mission:**

Making the dual-screen Android experience accessible to everyone.

---

**FreeDualScreen – Community-powered. Completely free.**
