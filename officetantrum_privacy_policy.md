# Privacy Policy for Office Tantrum: Stress Relief

**Last updated:** November 16, 2026

## Introduction

Office Tantrum: Stress Relief ("Office Tantrum", "the App", "we", "our" or "us") is a stress-relief game made by Akash Sinha, an individual developer based in India. You pick a cartoon 3D boss, can optionally put a face from a photo on it, and then punch, poke, pie and tickle it until you feel better.

This policy explains what information the App uses, where it goes, and how to remove it. The short version: **your photos, recordings and voice stay on your iPhone. We have no servers, no accounts, no analytics and no ads.**

---

## 1. Information We Collect

### 1.1 No Accounts, No Personal Information

Office Tantrum has no sign-up or login. We do **not** collect your name, email address, phone number, contacts, location, or advertising identifier. Nothing you do in the App is sent to us.

### 1.2 Face Photos (Optional)

You can choose a photo so the boss wears a cartoon version of a face. When you do:

- The photo is opened **only on your device**. Face detection, face shape and background removal run **on the device** using Google's open-source MediaPipe models, which are bundled inside the App
- The photo is **never uploaded** to us or to anyone else, and it is not used to identify anyone
- It is used **only** to place a face on the 3D cartoon character (and to tint the character's skin to match)
- The photo, the face outline and the face texture are kept **in memory only** while the App is running. They are not saved to the App's storage, and they are gone when you close the App or pick a different photo
- You can always skip this step and use the built-in cartoon boss instead

**Please only use your own face, or a face you have permission to use.** Office Tantrum is meant as a light-hearted way to blow off steam. Do not use it to harass, humiliate or impersonate anyone.

### 1.3 Microphone and Voice (Optional)

The App uses the microphone only when you ask it to:

- **Record a boss voice:** when you tap Record on the voice screen, the App records a short clip (up to 10 seconds) so the boss can say it when hit. You can also pick an audio file instead
- **Talk mode:** when you tap TALK during a fight, the microphone listens so the boss can answer back when you pause. The microphone closes when you tap TALK again, pause, or the fight ends
- Recordings and what you say are kept **in memory only**, are **never saved to storage**, and are **never uploaded**. They are discarded after the boss has answered, or when you close the App
- Where your device can recognise speech **fully on the device**, the App may use that to pick a reply that fits what you said. The App does not use online speech recognition, and your words are not stored
- The boss's spoken replies use your iPhone's built-in text-to-speech. Only the game's own lines are spoken, never anything you said

If you never tap Record or TALK, the App never asks for microphone access.

### 1.4 Data Stored on Your Device

The App saves a few small things in its private storage on your iPhone so the game remembers you between sessions:

- Volume settings, the last action you used, whether you have seen the tutorial, and the boss you picked (male or female)
- Game progress: your coin balance, the weapons you unlocked and equipped, defeats so far, the reason you picked last and, if you choose "Other", the short reason you typed (up to 40 characters)
- A list of purchase transaction IDs whose coins have already been added, so a purchase is never counted twice

This data never leaves your device and is deleted when you delete the App.

### 1.5 Coin Packs (In-App Purchases)

Coins can be earned by playing, or bought as optional coin packs. Coin packs are **consumable Apple In-App Purchases**:

- Payment is handled entirely by **Apple**. We never see your card, bank or billing details, or your Apple ID
- The App receives from Apple only what is needed to add the coins: the product, the localised price, and the transaction identifier
- We do not use RevenueCat or any other purchase service, and we have no server that receives purchase data

### 1.6 Usage, Diagnostics, Advertising

The App contains **no analytics SDK, no crash-reporting SDK, no advertising and no tracking**. Apple may collect crash and usage data from your device under its own privacy policy if you have chosen to share it with developers in iOS Settings.

---

## 2. How We Use Information

- **Face photo:** only to put a face on the 3D cartoon character, on your device
- **Microphone:** only to record a boss voice clip or to let the boss answer back in Talk mode, on your device
- **On-device storage:** only to remember your settings, coins and unlocked weapons
- **Purchases:** only to add the coins you bought

We do not sell, rent or share your information, and we do not use it for advertising or profiling.

---

## 3. Third Parties

- **Apple** processes In-App Purchases and provides the iOS text-to-speech voices. See [Apple's Privacy Policy](https://www.apple.com/privacy/).
- **Google MediaPipe** is open-source software bundled inside the App. It runs entirely on your device and does not send anything to Google.
- **Model download fallback:** the face models are bundled with the App. Only if those bundled files cannot be loaded does the App download the same public model files from Google's MediaPipe storage or the jsDelivr CDN. That request contains no photo or personal data, though, as with any download, the server can see your IP address.

There are no other third-party services in the App.

---

## 4. Storage, Retention and Security

- Photos and recordings are held in memory only and are discarded when you close the App or replace them
- Settings, progress and the purchase list stay in the App's private storage on your iPhone until you delete the App
- We keep no copy of anything, because nothing is sent to us
- Your data is protected by your iPhone's built-in security. We recommend using a passcode

---

## 5. Deleting Your Data

- **Photo or voice clip:** pick a new photo or remove the clip in the App, or simply close the App. They are not saved
- **Everything else:** delete Office Tantrum from your iPhone. This removes your settings, coin balance, unlocked weapons and purchase list
- **Microphone permission:** turn it off any time in iOS Settings > Office Tantrum > Microphone
- There is no account, so there is nothing to delete on our side. If you have a question anyway, email us (section 9)

Note: coins are consumable purchases stored on your device. If you delete the App, your coin balance is removed and cannot be restored.

---

## 6. Children's Privacy

Office Tantrum is not directed at children under 13, and we do not knowingly collect personal information from anyone. If you are a parent or guardian and have a concern, please contact us.

---

## 7. International Users

Everything the App does with your photos and voice happens on your device, wherever you are. Purchases are processed by Apple under Apple's policies.

---

## 8. Changes to This Policy

We may update this policy when the App changes. The "Last updated" date at the top will show the latest version, and significant changes will be noted in the App Store release notes. Continued use of the App after a change means you accept the updated policy.

---

## 9. Contact

**Email:** asquare938@gmail.com
**Subject:** Office Tantrum Privacy
**Developer:** Akash Sinha, India

---

## Summary

- Your face photos are processed **only on your iPhone**, never uploaded, and never saved
- Recordings and Talk mode audio stay **in memory on your iPhone** and are never uploaded or saved
- No accounts, no analytics, no ads, no tracking
- Coin packs are Apple In-App Purchases; we never see payment details
- Delete the App to delete everything

See also: [Office Tantrum Support](support.html?file=officetantrum_support.md)

<!--
App Store privacy label (suggested answers for App Store Connect > App Privacy):

Data Collection: "No, we do not collect data from this app."

Reasoning:
- Face photos: processed on device only, held in memory, never transmitted -> not "collected" under Apple's definition (data is collected only if it leaves the device to the developer or third parties).
- Audio (recordings / Talk mode): on device only, in memory, never transmitted -> not collected.
- Speech recognition: only the on-device mode is used -> not collected.
- Purchases: handled by Apple StoreKit; the developer has no server and no third-party purchase SDK -> not collected by the developer (Apple's own purchase data does not need to be declared).
- No analytics, crash reporting, ads or identifiers.
- Tracking: No.

If a future version adds RevenueCat, analytics, crash reporting or any server, update this to declare Purchases / Identifiers / Diagnostics accordingly.

Info.plist strings needed for the iOS build:
- NSMicrophoneUsageDescription: "Office Tantrum uses the microphone only when you tap Record or TALK, so the boss can use your voice clip or answer back. Audio stays on your iPhone and is never uploaded."
- NSCameraUsageDescription (only if the iOS photo picker offers Take Photo): "Take a photo to put a cartoon face on the boss. The photo is processed on your iPhone and never uploaded."
- NSSpeechRecognitionUsageDescription (only if WKWebView exposes on-device SpeechRecognition with processLocally on the target iOS version; BossReplies.ts bails out when SpeechRecognition.available is missing): "Office Tantrum recognises your words on your iPhone so the boss can answer back. Your speech is never uploaded."
- No photo library permission is needed when using the system photo picker.
-->
