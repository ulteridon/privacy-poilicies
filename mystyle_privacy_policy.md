# Privacy Policy for Patra: Festival Poster Maker

**Last updated:** November 16, 2026

Patra ("we", "our", "us") is a festival poster and greeting-card maker for iPhone and Android. It places your name and photo onto ready-made designs and lets you share the result. Patra is published by Akash Sinha, an individual developer based in India.

This policy explains what Patra does with your information. In short: your name, photos and preferences stay on your phone. The only things that leave it are (1) requests for our public design files, (2) an anonymous ID and purchase records used to manage Patra Pro, and (3) if you choose to use **AI Create**, the text and pictures you put into that request.

---

## 1. What stays on your phone

### Your name and photos

You can enter a display name (and how it is written in Hindi) and add photos of yourself on the Profile screen, or the first time you personalise a poster. Patra keeps up to 12 of your photos so you can switch between them, and remembers where you placed a photo on each design.

- Stored only in Patra's private storage on your phone
- Never uploaded to us or to anyone else (the one exception is a photo you choose to attach in AI Create, see section 3)
- You can change your name or remove any saved photo at any time from the Profile screen

### Interests, state and faith (all optional)

In Profile → Personalisation you can pick what you like to share (for example Birthday, Diwali, Good morning), and optionally a state or union territory from a list and your faith (or "Prefer not to say").

- Used only on your phone, to put relevant designs and festivals first and decide which categories to keep for offline use
- Never uploaded, sold or used for advertising
- "State" is the one you pick from a list. Patra does not use GPS and does not ask for location permission

### Posters you make

Posters are composed on your phone. Converted pictures and Studio edits stay on your phone. Pictures you make with AI Create are saved in Patra on your phone (the last 60), and you can delete any of them with a long-press.

### Other app data

Patra also keeps small settings (for example whether you have seen a tip), your last known Pro status (so Pro works offline), and a copy of downloaded designs so the app works without internet.

---

## 2. Permissions

- **Photos (iPhone and Android):** Patra uses the system photo picker. It hands Patra only the photo you choose. Patra does not read, scan or index the rest of your library, and it does not ask for Photos, media or storage permission on either platform.
- **Internet:** to download designs, check Patra Pro and, if you use it, AI Create.
- Patra does **not** use the camera, microphone, location, contacts or tracking (no App Tracking Transparency prompt on iPhone).

---

## 3. What leaves your phone, to whom, and why

### a) Design downloads (Cloudflare and GitHub)

Templates, background images and captions are published by us and downloaded from our content server on **Cloudflare Pages**, with **GitHub** as a backup when Cloudflare cannot be reached. These requests ask only for public files; they contain none of your personal data. Like any website, these hosts can see your IP address and basic request details (device type, time) under their own policies.

### b) Patra Pro purchases (Apple, Google, RevenueCat)

Patra Pro is optional. It removes the watermark from shared designs. It is sold as a monthly or yearly subscription (and, where offered, a one-time lifetime option).

- **On iPhone, payment is handled by Apple** through In-App Purchase. **On Android, by Google Play.** We never see your card, UPI, bank or billing details, or your Apple ID or Google account.
- To know whether you have Pro, Patra uses **RevenueCat** (RevenueCat, Inc.). RevenueCat receives a random anonymous ID created on your phone, your purchase receipt and purchase history for Patra (product, price, currency, purchase and renewal dates), your country or store region, and your app and OS version. It does not receive your name, photos, interests, state or faith.
- We use this only to unlock Pro, restore it on a new phone, and see overall subscription numbers.
- Patra contacts RevenueCat to check your Pro status even if you never buy anything; in that case there is no purchase data, only the anonymous ID.

### c) AI Create (only if you use it)

AI Create makes a new picture from your description. It is switched on from our side and may not be available yet on your device. Nothing is sent unless you tap Create.

When you tap Create, Patra sends to our **Patra AI server** (run by us on **Cloudflare Workers**):
- what you typed (description, the wording to print, a name, and any optional shop or event details such as a business name, phone number or address)
- your choices (purpose, style, size, quality)
- any pictures you attached (for example your photo, a logo or a product), shrunk to at most 1024 pixels
- the anonymous RevenueCat ID and a random secret created on your phone, so the server knows which credit balance is yours

Our server passes your text and pictures to **Google's Gemini API** (Google LLC), which draws the picture. We use Google's paid API service. Under Google's terms for that service, your requests are not used to train Google's models; Google may keep them for a limited time to detect abuse. See [Gemini API Additional Terms](https://ai.google.dev/gemini-api/terms).

What our AI server keeps:
- **Your finished picture:** kept for 1 hour so your phone can download it if the connection drops, then deleted automatically. We do not keep your text or the pictures you attached after the request is done.
- **Your credit balance:** linked to the anonymous ID. It holds the number of credits, credits spent, recent job IDs, daily picture counts, whether you have bought credits, and the random secret. It is kept while you have credits, so they are not lost.
- **Purchase markers:** the store transaction ID of each credit pack, so the same purchase is never counted twice.
- **Abuse limits:** a daily count of pictures and new installs per network (based on your IP address). It is deleted automatically after about a day.

**Credit packs** are one-time purchases: Apple In-App Purchase on iPhone, Google Play on Android, recorded through RevenueCat as in (b). After a purchase, our server asks RevenueCat which packs your anonymous ID has bought and adds the credits.

Please only attach photos of people who are happy for you to use them, and do not put sensitive information in a description.

### d) Sharing

When you tap Share, your phone's own share sheet opens and you choose where the poster goes (WhatsApp, Instagram, Save Image and so on). We do not see or keep what you share; the app you pick handles it under its own policy.

### What we never do

- We do not sell or rent your data
- No advertising, no ad SDKs, no tracking across other apps or websites
- No analytics or crash-reporting SDK. Apple and Google may give us anonymous, aggregated crash and usage statistics through their developer consoles if you have agreed to share them with developers

---

## 4. Third parties

| Service | What it is for | Policy |
| --- | --- | --- |
| Apple (App Store, In-App Purchase) | Download and payment on iPhone | [apple.com/privacy](https://www.apple.com/privacy/) |
| Google Play | Download and payment on Android | [policies.google.com/privacy](https://policies.google.com/privacy) |
| RevenueCat | Patra Pro and credit-pack status | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |
| Cloudflare (Pages, Workers) | Design downloads; Patra AI server | [cloudflare.com/privacypolicy](https://www.cloudflare.com/privacypolicy/) |
| GitHub | Backup for design downloads | [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) |
| Google Gemini API | Drawing AI Create pictures (only if you use it) | [Gemini API Additional Terms](https://ai.google.dev/gemini-api/terms) |

These services may process data outside India, including in the United States.

---

## 5. Storage and retention

- **On your phone:** kept until you delete it in the app or uninstall Patra. Uninstalling removes everything Patra stored. Photos in your own gallery are not affected.
- **RevenueCat:** purchase records for as long as needed to manage your purchases and meet legal and tax duties, or until you ask us to delete them.
- **Patra AI server:** finished pictures 1 hour; per-network counters about 1 day; credit balance and purchase markers until you ask us to delete them.
- **Apple and Google:** keep their own purchase records under their own policies.

---

## 6. Deleting your data

- **On your phone:** remove photos in Profile, delete AI creations with a long-press, or uninstall Patra to remove everything.
- **RevenueCat and AI credit records:** Patra has no accounts, so we cannot look you up by name. Email us at asquare938@gmail.com with your Apple order ID (from your App Store receipt email) or Google Play order number, and we will delete the matching RevenueCat customer record and any AI credit balance within 30 days. Deleting them removes any unused AI credits and means a later "Restore purchases" creates a fresh record.
- **Cancel a subscription:** on iPhone, Settings → [your name] → Subscriptions → Patra. On Android, Google Play → Payments & subscriptions → Subscriptions. Deleting the app does not cancel a subscription.

---

## 7. Children

Patra is not directed at children under 13, and we do not knowingly collect information from them. If you believe a child has sent us information (for example through AI Create), email us and we will delete it.

---

## 8. Security

Your data on the phone is protected by your device's own security; we recommend a screen lock. Connections to our content and AI servers and to RevenueCat use HTTPS. Your AI credit balance can only be used by the phone that holds its secret. No system is perfectly secure, but we keep what we hold to the minimum described here.

---

## 9. Legal requests

We may disclose information if the law requires it. Because we hold almost nothing about you, there is usually nothing to disclose.

---

## 10. Changes to this policy

If we change how Patra handles data, we will update this page and the "Last updated" date, and mention significant changes in the app or its store listing.

---

## 11. Contact

**Akash Sinha** (individual developer), India
**Email:** asquare938@gmail.com
**Subject line:** Patra Privacy

---

See also our [Terms of Service](policy.html?file=mystyle_terms.md) and [Support page](support.html?file=mystyle_support.md).

<!--
App Store privacy label (App Privacy questionnaire) - suggested answers for Patra, iOS 1.0.

Tracking: NO. No data is used to track users across other companies' apps or websites. No ATT prompt.

Data collected (all "Not linked to you", purpose "App Functionality" only; none used for analytics, ads or personalisation off-device):

1. Purchases > Purchase History  - RevenueCat (Pro subscription + AI credit packs). Not linked. App Functionality.
2. Identifiers > User ID - RevenueCat anonymous app user ID ($RCAnonymousID), also used as the AI credit wallet key. Not linked. App Functionality.
   (Some developers treat a random anonymous ID as not needing disclosure; declaring it is the conservative choice.)

Only if AI Create is switched on in the iOS build (app_config.json "ai.endpoint" set):
3. User Content > Photos or Videos - photos the user attaches in AI Create (sent to our Cloudflare Worker and Google Gemini). Not linked. App Functionality.
4. User Content > Other User Content - prompt text, wording, name printed on the poster, optional business name/phone/address. Not linked. App Functionality.
   (Conservative option: also tick Contact Info > Name / Phone Number / Physical Address, Not linked, App Functionality, because users may type them into AI Create.)

Not collected: Contact Info (unless choosing the conservative option above), Health, Financial Info (Apple handles payment), Location (state is picked from a list and stays on device), Sensitive Info (faith stays on device), Contacts, Browsing/Search History, Usage Data, Diagnostics (no analytics or crash SDK), Other Data.

Note: name, profile photos, interests, state and faith are processed only on device and are NOT "collected" under Apple's definition.
Apple guideline 5.1.2(i): before the first AI Create request, show an in-app notice that the text and photos are sent to Google Gemini via our server, and get the user's OK.
-->
