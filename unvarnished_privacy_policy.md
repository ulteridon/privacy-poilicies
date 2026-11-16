# Privacy Policy for Unvarnished: Honest Feedback

**Last updated:** November 16, 2026

## Introduction

Unvarnished: Honest Feedback ("Unvarnished," "the App," "we," "our," or "us") gives you blunt, structured feedback on things you write or describe, such as resume bullets, a startup pitch, a dating bio, or a cover letter. This Privacy Policy explains what information the App uses, where it goes, and how long it is kept.

Unvarnished is published on the App Store by Akash Sinha, an individual developer based in India.

The short version: there is no account and no sign-up. The text you submit is sent to our server and on to an AI provider only so the App can write your feedback, and it is not stored on our server after that. Your conversations are saved on your iPhone.

---

## 1. Information We Collect

### 1.1 Text You Submit for Feedback

When you paste text and ask for feedback, that text is sent from your device to our server, which forwards it to a third-party AI model to generate your feedback and score. If you push back on a verdict, your reply and the earlier verdict are sent along with your original text so the AI has context.

- **We ask first.** Before your first request, the App shows a screen explaining that your text will be sent to our server and to our AI provider, Anthropic (see section 3). Nothing is sent unless you agree. If you decline, the App cannot generate feedback.
- We use it **only** to produce the feedback you asked for
- Our server does **not** save copies of your text or the feedback after the request is finished
- We do **not** read your submissions, sell them, or use them for advertising
- We do **not** use your submissions to train AI models

**Please do not include sensitive personal details** (for example government ID numbers, bank details, passwords, health information, or other people's private information) in what you submit. If you are pasting a resume, consider removing your phone number, home address, and email first; the feedback does not depend on them.

### 1.2 Anonymous Install ID

The first time you open the App, it creates a random identifier and stores it on your device. This ID is not your name, email, phone number, or Apple's advertising identifier (IDFA), and it is not linked to your Apple ID. The App shows it as the **Support ID** in Settings.

It is sent with each feedback request **only so our server can apply rate limits** (a cap on how many requests one install, and one IP address, can make per minute and per day) and prevent abuse of the service.

- Our server does **not** check whether you have Pro and does not know whether you have bought anything.
- Our server does **not** save the ID in a database or in its logs. Rate-limit counters are kept only temporarily in the server's working memory and are discarded automatically.
- Your daily verdict count (for the free and Pro daily limits) is tracked **on your device**, not on our server.

### 1.3 Technical Request Data

Like any internet service, our server receives your device's IP address when the App contacts it. Our server uses the IP address, together with the install ID, only for the short-term rate limits described in section 1.2, and holds it in memory only.

Our own server logs record only which endpoint was called, the app name, the result status, and how long the request took. They do **not** contain your IP address, your install ID, the text you submitted, or the feedback you received. Our hosting provider (see section 3) may keep its own standard request logs, which can include IP addresses, for security and operations, for **no more than 30 days**.

### 1.4 Purchases (Unvarnished Pro)

Unvarnished Pro is an optional monthly or yearly subscription.

- **Purchases are handled entirely by Apple** through In-App Purchase. We never see your card or billing details.
- The App uses Apple's StoreKit directly on your iPhone to show prices, make and restore purchases, and check whether Pro is active. To do this it only reads your own StoreKit entitlements on the device. No third-party subscription or purchase-management service is used.
- **Nothing about your purchases is sent to us.** Your receipts, transaction details, and subscription status are not sent to our server or to any other service we run. Apple gives us aggregate sales and subscription reports in App Store Connect, which do not identify you to us.

### 1.5 Information We Do NOT Collect

- No name, email address, phone number, or account credentials (there are no accounts)
- No contacts, photos, location, camera, or microphone access
- No advertising identifier (IDFA) and no tracking across other apps or websites
- No advertising SDKs, no third-party analytics SDKs, and no third-party subscription or purchase-management services

---

## 2. How We Use Information

- **Your text:** to generate the feedback and score you requested, and nothing else
- **Anonymous install ID and IP address:** to apply rate limits and prevent abuse, and nothing else
- **Technical request data:** to keep the service secure and working
- **Pro status:** checked on your device, from your own StoreKit entitlements, to unlock Pro limits; it is not sent to us

---

## 3. Third Parties

We share data only with the services needed to run the App:

- **AI provider** – Your submitted text is forwarded by our server to a third-party AI model provider to generate feedback. Today that provider is **Anthropic, PBC** (the Claude models). The provider processes the text under its commercial API terms, does not use it to train its models, and may keep it for a limited period for safety and abuse monitoring. See [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy). If we change AI provider, we will update this policy.
- **Our server hosting provider** – Our server runs on **Vercel** (Vercel Inc.), which processes requests on our behalf and does not use the data for its own purposes. See [Vercel's Privacy Policy](https://vercel.com/legal/privacy-policy).
- **Apple** – App distribution, In-App Purchase payments, and subscription management. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). If you opt in to share analytics with app developers in iOS Settings, Apple may also share anonymous crash and usage statistics with us.

We do **not** sell, rent, or trade your information, and we do not share it with advertisers or data brokers.

We may disclose information if required by law, such as a valid court order. Because we do not keep your submissions, in practice there is very little we could disclose.

---

## 4. Storage and Retention

| Data | Where it is kept | How long |
|---|---|---|
| Your conversations and feedback | On your iPhone only | Until you delete them or delete the App |
| Submitted text on our server | Our server, in memory while processing | Not stored after the request finishes |
| Submitted text at the AI provider | Anthropic | A limited period under its API terms, for safety monitoring only |
| Anonymous install ID | Your device | Until you delete the App |
| Daily verdict count and Pro status | Your device only | The count resets daily; Pro status is re-checked with StoreKit on your device |
| Rate-limit counters (install ID, IP address) | Our server, in temporary memory only | Short-lived; never written to a database or log |
| Our server logs (endpoint, status, timing; no content, IP address, or install ID) | Our server (Vercel) | Up to 30 days |
| Hosting provider request logs (may include IP address) | Vercel | Up to 30 days |
| Subscription and purchase records | Apple only | Under Apple's own policy |

Data processed by our providers may be stored outside India, including in the United States.

---

## 5. Deleting Your Data

- **Conversations:** delete any conversation inside the App. Deleting the App removes all conversations and the anonymous ID from your device.
- **Server-side data:** we do not keep your submissions, and our server keeps no message counts, purchase records, or other records tied to your anonymous ID, apart from the short-lived rate-limit counters described in section 1.2. If you have a question or request about your data, email us (section 9); including the Support ID from the App's Settings screen helps us answer.
- **Subscription:** cancelling does not delete data by itself. Manage or cancel Pro in iOS **Settings → [your name] → Subscriptions**. Apple keeps its own purchase records under Apple's policy.

---

## 6. Security

Data travelling between the App, our server, and the AI provider is encrypted in transit (HTTPS). The AI provider's keys are kept on our server, never in the App. No method of transmission or storage is 100% secure, but we keep what we hold to a minimum so there is little to protect in the first place.

---

## 7. Children's Privacy

Unvarnished is not directed at children under 13, and we do not knowingly collect information from children under 13. If you are a parent or guardian and believe your child has used the App and provided information, contact us and we will help remove it.

---

## 8. Changes to This Privacy Policy

We may update this policy from time to time, for example if we change AI provider or add a feature. When we do, we will change the "Last updated" date above, and significant changes will be noted in the App or its App Store listing. Continued use of the App after changes means you accept the updated policy.

---

## 9. Contact

Questions about this policy or your data:

- **Email:** asquare938@gmail.com
- **Subject:** Unvarnished Privacy
- **Developer:** Akash Sinha, India

See also: [Unvarnished Support](support.html?file=unvarnished_support.md)

<!--
App Store privacy label (suggested answers for App Store Connect > App Privacy):

Tracking: NO. (No IDFA, no ad SDKs, no data shared with data brokers or for cross-app advertising.)

Data collected:
1. User Content > Other User Content (text submitted for feedback; on a push-back, the reply and the earlier verdict)
   - Purpose: App Functionality
   - Linked to user: NO (not stored after processing; no account)
   - Used for tracking: NO
2. Identifiers > Device ID (the app-generated random install ID, sent as X-Install-Id and shown as the Support ID)
   - Purpose: App Functionality. Used ONLY for server-side rate limiting / abuse prevention; held in memory, never stored in a database or logs.
   - Linked to user: YES (marked linked to be cautious, since it accompanies every request)
   - Used for tracking: NO
3. Purchases > Purchase History: NOT collected. Purchases use Apple StoreKit directly (ios/App/App/ProStorePlugin.swift plus
   @capgo/native-purchases). The app only reads its own StoreKit entitlements on the device and sends nothing about purchases
   to the server. No third-party purchase service. The server has no Pro check.
4. Diagnostics: NOT collected by the app (no crash/analytics SDK). Apple's own opt-in crash sharing does not need to be declared.

Not collected: Contact Info, Health, Financial Info, Location, Sensitive Info, Contacts, Browsing/Search History, Usage Data, Purchases, Other Data.
Note: the IP address is used only for short-term in-memory rate limiting and may appear in the hosting provider's request logs (<=30 days).
It is not used to derive location and does not need its own row.
-->
