# Privacy Policy for Voltaura: Charging Animation

**Last updated:** November 16, 2026

## Introduction

This Privacy Policy explains how Voltaura: Charging Animation ("Voltaura", "the app", "we", "our", or "us") handles your information on iPhone. Voltaura is published on the App Store by Akash Sinha, an individual developer based in India.

The short version: Voltaura works entirely on your iPhone. It has no account, no ads, no analytics, and no servers of its own. The only time anything leaves your device is when you buy or restore Voltaura Pro, which is handled by Apple.

## What Voltaura Does

Voltaura plays full-screen charging animations. Because iOS does not let apps react to a charger by themselves, you set up an automation in Apple's Shortcuts app ("When charger is connected, open Voltaura"). When the automation opens the app, Voltaura shows your chosen animation along with your battery level.

## Information We Collect

### Information that stays on your device

Voltaura stores the following on your iPhone only:

- **Battery level and charging state:** Read from iOS while the app is open, so the animation can show your charge percentage and whether the phone is charging. This is not saved as a history and is never sent anywhere.
- **Your settings:** Your selected animation and display preferences.
- **Custom background photo (optional):** If you choose a background, you pick one photo with Apple's system photo picker. Voltaura only receives the photo you pick and keeps a copy inside the app's own storage so it can be shown behind the animation. It is never uploaded.
- **Pro status:** Whether Voltaura Pro is unlocked on this device.

### Information we do NOT collect

- We do not ask for your name, email address, or any account details. There is no sign-in.
- We do not access your full photo library, contacts, location, camera, microphone, or health data.
- We do not use analytics, crash-reporting, advertising, or tracking SDKs.
- We do not use the advertising identifier (IDFA) and do not track you across apps or websites.
- We do not send any data to our own servers. We do not have any.

## How Information Is Used

The data stored on your device is used only to:

- Play your selected charging animation
- Show your current battery percentage and charging state
- Display your custom background photo, if you set one
- Unlock Pro animations after a purchase

## In-App Purchases

Voltaura offers one optional, one-time (non-consumable) purchase called **Voltaura Pro**, sold through Apple In-App Purchase using Apple's StoreKit.

- Apple processes the payment. We never see or store your card or payment details.
- Apple tells the app on your device whether Pro has been purchased. We do not run our own purchase server and do not use any third-party purchase service.
- Apple shares standard sales reports with developers through App Store Connect. These reports do not identify you personally to us.
- You can restore your purchase on any device signed in to the same Apple Account.

## Third Parties

- **Apple:** App distribution through the App Store, In-App Purchase, the Shortcuts automation that opens the app, and the system photo picker. Apple's handling of your data is described in [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

Voltaura does not share data with any other company. We do not sell your information.

## Network Use

Voltaura does not make network requests of its own. The only network activity is Apple's StoreKit communicating with the App Store when you view the price of, buy, or restore Voltaura Pro. All animations are bundled inside the app and work offline.

## Storage and Retention

- Everything Voltaura stores lives in the app's private storage on your iPhone.
- Your settings and background photo stay until you change or remove them, or until you delete the app.
- If iCloud Backup or a computer backup is enabled on your iPhone, iOS may include the app's data in that backup, under Apple's control.

## Deleting Your Data

- **Background photo:** Remove it at any time from the app's settings. The original in your Photos library is never changed.
- **Everything else:** Delete the app from your iPhone. This removes all of Voltaura's data from the device.
- **Shortcuts automation:** Open the Shortcuts app, go to Automation, and delete the "When charger is connected" automation.

Because we hold no data about you on any server, there is nothing for us to delete on our side. Your Pro purchase record is kept by Apple so it can be restored.

## Children's Privacy

Voltaura is not directed at children under 13, and we do not knowingly collect personal information from anyone, including children. The app does not collect personal information from any user.

## Changes to This Policy

If Voltaura's data practices change (for example, if a new feature needs data to leave your device), we will update this policy before that version is released and change the "Last updated" date above.

## Contact

If you have any questions about this Privacy Policy, please contact:

**Akash Sinha**
**Email:** asquare938@gmail.com
**Subject:** Voltaura Privacy

<!--
App Store privacy label (suggested answers for App Store Connect > App Privacy), iOS 1.0 as designed:

- Do you or your third-party partners collect data from this app? -> NO ("Data Not Collected").
  Reasoning: no account, no analytics, no ads, no crash SDK, no own server. Battery level/state and the
  custom background photo are processed only on device and never transmitted, which Apple does not count
  as "collection". StoreKit purchases are handled by Apple; Apple's own processing does not need to be declared.
- Tracking: NO. No IDFA, no App Tracking Transparency prompt needed.
- Linked to user: N/A (nothing collected).
- Privacy manifest (PrivacyInfo.xcprivacy): declare NSPrivacyTracking = false, no collected data types,
  and the required-reason API for UserDefaults (CA92.1, app's own data). Add File timestamp / Disk space
  reasons only if a plugin uses them (check Flutter plugins' bundled manifests).
- Revisit this answer if you later add RevenueCat, Firebase, Crashlytics, any analytics, ads, or remote content.
-->
