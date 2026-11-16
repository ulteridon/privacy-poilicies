# Privacy Policy for Nursery Night: Tower Defense

**Last updated:** November 16, 2026

## Introduction

This Privacy Policy explains how Nursery Night: Tower Defense ("Nursery Night", the "App", "we", "our" or "us") handles your information. Nursery Night is a single-player tower defense game for iPhone, published by Akash Sinha, an individual developer based in India.

The short version: **Nursery Night does not collect any personal data.** The game runs entirely on your device. It has no account, no ads, no analytics, no in-app purchases, and it does not send anything to us or to anyone else.

---

## 1. What We Collect

**Nothing.** We do not collect, receive or store any information about you, including:

- Your name, email address, phone number or any account details
- Your location
- Contacts, photos, camera, microphone or files
- Advertising identifiers or device identifiers
- Usage statistics, analytics, crash reports or diagnostic data

There is no sign-up and no login. You never type any personal information into the game.

## 2. What the Game Saves on Your Device

To remember your progress, Nursery Night keeps a small save file in the App's private storage on your iPhone. It contains only game data:

- In-game coins and moonstones (play currency with no real-money value)
- Toys and skins you have unlocked, and which outfit, cradle and pacifier you have equipped
- Wins and best times for each game mode
- A list of your last 20 nights played (mode, won or lost, length of the night, and the date)
- Your daily gift streak and the date you last claimed it
- Your settings: language, sound on or off, and graphics quality

This save never leaves your device. We cannot see it.

## 3. How This Information Is Used

The save file is used only to run the game: to keep your progress between sessions, show your records on the Night Board, decide whether today's daily gift is ready (using your device's clock), and apply your chosen settings.

## 4. Network Use

Nursery Night does not make network connections. All 3D models, sounds, text and game content are bundled inside the App, so it works fully offline. It does not contact our servers (we do not run any) or any third-party server.

## 5. Permissions

Nursery Night does not ask for any iOS permissions. It does not use your camera, microphone, photo library, location, contacts, notifications or tracking.

## 6. Third Parties

The App contains **no** third-party analytics, advertising, tracking or crash-reporting SDKs.

- **Apple** distributes the App through the App Store. Apple may collect information about your download and, if you have opted in, share aggregated crash and usage data with developers, under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). We do not receive anything that identifies you.

## 7. In-App Purchases and Ads

Version 1.0 is free, with **no in-app purchases and no ads**. The coins, moonstones, shop and toy draw inside the game use play currency earned by playing; they cannot be bought with real money.

If we ever add in-app purchases, they would be handled by Apple In-App Purchase. We would never see your card or payment details, and we would update this policy first.

## 8. Storage and Retention

Your save stays on your device until you reset it or delete the App. Like other app data, it may be included in your own iPhone backups (iCloud or computer), which are controlled by you and Apple, not by us.

## 9. Deleting Your Data

You are always in control:

- **Reset progress:** in the game, open **Settings → Reset all progress**. This erases your coins, toys and records but keeps your language, sound and graphics settings.
- **Delete everything:** delete the App from your iPhone. This removes the save file completely.

Because we never receive any of your data, there is nothing for us to delete on our side.

## 10. Children's Privacy

Nursery Night is not directed at children under 13. That said, the App does not collect personal information from anyone of any age, does not show ads, and has no chat or social features.

## 11. Possible Future Features

We may add **Apple Game Center** (for leaderboards or achievements) in a later version. If we do, it would be optional, handled by Apple under your Game Center settings, and we would update this policy before releasing it.

## 12. Changes to This Policy

If we change this policy, we will post the new version on this page and update the "Last updated" date above. Material changes will be made before the related App update is released.

## 13. Contact

If you have any questions about this Privacy Policy, please contact:

**Akash Sinha**
**Email:** asquare938@gmail.com
**Subject:** Nursery Night Privacy

---

**Last updated:** November 16, 2026

<!--
App Store privacy label (App Store Connect -> App Privacy), suggested answers for Nursery Night 1.0:

- "Do you or your third-party partners collect data from this app?"  -> No.
- Resulting label: "Data Not Collected".
- Tracking: No (no ATT prompt, no IDFA, no ad or analytics SDKs).
- Basis: the game makes no network calls; the only storage is a localStorage save
  ("nurserynight.save.v2") inside the app's WKWebView; Info.plist declares no permission usage strings;
  the iOS Podfile contains only Capacitor core, no plugins.

If Game Center is added later: Game Center data is collected by Apple, not by the developer, so the
label can usually stay "Data Not Collected" unless you also send scores or IDs to your own server.
Re-check before each release if any SDK (analytics, ads, crash reporting, RevenueCat) is added.

Age rating questionnaire hint: cartoon/fantasy violence (mild) - a closet monster attacks doors; no
unrestricted web access, no user-generated content, no gambling with real money (the "Draw" uses
earned play currency only; consider whether Apple's "simulated gambling" question applies).
-->
