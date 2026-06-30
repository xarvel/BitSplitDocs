# BitSplit Privacy Policy

**Effective date:** June 30, 2026  
**Last updated:** June 30, 2026

This Privacy Policy describes how **BitSplit** (“the App”), published by **IL DARK** (“we”, “us”, “our”), handles information when you use the mobile application available on the Apple App Store and Google Play.

If you have questions, contact us at **valiullin.arthur.dev@gmail.com** or visit our [Support page](https://xarvel.github.io/BitSplitDocs/support).

---

## Summary

BitSplit is an offline arcade game. We do **not** require an account, show ads, use analytics SDKs, or transmit your data to our servers. The App stores a small amount of game data **locally on your device** so your best scores and settings persist between sessions.

---

## Information We Collect

**We do not collect personal information.**

The App does not collect, transmit, or sell:

- name, email address, phone number, or other contact details  
- location data  
- device identifiers for tracking or advertising  
- payment information (the App has no in-app purchases)  
- photos, files, contacts, or calendar data  
- audio recordings (the App does **not** use your microphone)

---

## Information Stored Locally on Your Device

To provide core game functionality, the App saves the following data **only on your device** using local storage (AsyncStorage). This data is **not sent to us** and is **not linked to your identity**:

| Data | Purpose |
|------|---------|
| Best score per difficulty level | Show your personal high scores |
| Control scheme preference (joystick or arrows) | Remember your chosen controls |

You can delete this data at any time by clearing the App’s storage or uninstalling the App.

---

## Permissions and Device Features

The App may request or use device capabilities solely for gameplay:

| Feature | Use | Data collected |
|---------|-----|----------------|
| **Audio playback** | Sound effects and background music | None |
| **Haptic feedback** | Tactile feedback during gameplay | None |
| **Screen orientation** | Lock to portrait mode during play | None |

**Microphone:** BitSplit does **not** record or access your microphone. On Android, audio-related permissions may appear in the system manifest because of the audio playback library; the App only plays preloaded sound files and never captures audio input.

The App works **fully offline**. It does not need an internet connection to run and does not send gameplay data over the network.

---

## Third-Party Services

BitSplit does **not** integrate third-party analytics, advertising, crash reporting, or social login services.

Distribution platforms (Apple App Store, Google Play) may collect information about downloads and device compatibility according to their own privacy policies. We do not receive that information from them in a form that identifies you personally through the App.

---

## Children’s Privacy

BitSplit is suitable for general audiences (App Store age rating 4+; Google Play Everyone). We do not knowingly collect personal information from anyone, including children under 13 (or under 16 where applicable under GDPR). Because we do not collect personal data, no parental consent mechanism is required for data collection—we simply do not collect it.

If you believe we have inadvertently received personal information about a child, contact **valiullin.arthur.dev@gmail.com** and we will delete it.

---

## Data Retention

Locally stored game data remains on your device until you clear app data or uninstall the App. We do not retain copies on our servers because we do not receive that data.

---

## Your Rights

Depending on your location (including the EEA/UK under GDPR, or California under CCPA/CPRA), you may have rights regarding personal data. Because BitSplit does not collect or process personal data, most of these rights are not applicable. You can always:

- delete local App data via your device settings, or  
- uninstall the App  

To exercise any privacy-related request, email **valiullin.arthur.dev@gmail.com**.

---

## International Users

BitSplit is offered globally. Local data stays on your device; we do not transfer personal data across borders because we do not collect it.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will revise the “Last updated” date above. Material changes may also be noted in App Store or Google Play release notes. Continued use of the App after changes means you accept the updated policy.

---

## Contact Us

**IL DARK**  
Email: **valiullin.arthur.dev@gmail.com**  
Website: **https://bitsplit.app**

App identifiers:

- iOS: `com.xarvel.bitsplit`  
- Android: `com.xarvel.bitsplit`

---

## Store Console Reference (for submission)

Use the public URL **https://xarvel.github.io/BitSplitDocs/privacy-policy** in App Store Connect and Google Play Console.

### Apple App Store Connect — App Privacy

| Question | Answer |
|----------|--------|
| Do you or your third-party partners collect data from this app? | **No — Data Not Collected** |
| Tracking | **No** |

Local high scores and control preferences stay on device only and are not transmitted; under Apple’s definitions this is not “collected” by the developer.

### Google Play Console — Data safety

| Field | Answer |
|-------|--------|
| Does your app collect or share any of the required user data types? | **No** |
| Is all of the user data collected by your app encrypted in transit? | N/A (no data transmitted) |
| Do you provide a way for users to request that their data is deleted? | Users can clear app data or uninstall; no server-side data exists |

If Play Console asks about on-device storage: scores and settings are stored locally only, never leave the device, and are not linked to an account.

### Google Play — Permissions disclosure

Declare that the App uses audio for playback only. Microphone is not used. No location, contacts, or identity permissions are requested for data collection.
