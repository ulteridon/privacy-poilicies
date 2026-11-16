# Privacy Policy for Hirewise

**Last updated:** November 16, 2026

## Introduction

Hirewise: ATS Resume Builder ("Hirewise", "the App", "we", "our" or "us") is an iPhone app that helps you write a resume tailored to a specific job. You paste a job description, type or paste your own resume details, and the App uses an AI model to produce a tailored, ATS-friendly resume that you can save as a PDF.

Hirewise is made by Akash Sinha, an individual developer based in India. This policy explains what information the App handles, where it goes, and what choices you have.

**The short version:** to write your resume, the App has to send the text you enter (your resume details and the job description) to our server, which passes it to a third-party AI provider. That text is personal data. We ask for your permission in the App before the first upload, we do not keep the text after your request is finished, and we do not sell it or use it for advertising.

---

## 1. Information We Collect

### 1.1 Resume Details and Job Descriptions You Enter

To generate a resume you provide:

- **Your resume details**, for example your work history, education, skills and achievements, plus contact details for your PDF header. You decide what to include.
- **A job description** that you paste or type.

When you tap to generate a resume, this text is sent over an encrypted connection (HTTPS) to our server and from there to our AI provider (see section 3). It is used **only** to produce your tailored resume and is returned to your device.

**Contact details:** if you fill in your details using the App's form, the contact fields (name, email, phone, city and links) stay on your iPhone. They are added to the PDF header on your device and are **not** sent to our server or the AI provider. If you choose to paste an existing resume instead, everything you paste is sent, including any contact details it contains, so you may want to remove them before pasting.

Because resumes usually contain personal information, the App shows a consent screen **before your first upload** explaining that your text will be sent to our server and an AI provider. Nothing is uploaded unless you agree. If you do not agree, you can still use the parts of the App that work on your device, but you cannot generate an AI resume.

Please leave out anything you do not want processed, such as government ID numbers, date of birth, or health information. A resume does not need them.

### 1.2 Information Stored on Your Device

The App keeps the following **on your iPhone only**, in the App's private storage:

- Resume details and job descriptions you have entered, so you can edit and reuse them
- Resumes the App has generated, and the PDF files created from them
- Your credit balance, and the IDs of purchases already credited (so a purchase is never counted twice)
- Your consent choice
- The random install ID described in section 1.3

PDFs are created on your device. They leave your device only if you choose to share them or save them somewhere else, for example to the Files app, email or a cloud drive, using the iOS share sheet.

### 1.3 Technical Information Sent With Each Request

When the App contacts our server, the request also includes limited technical information:

- Your device's IP address (as with any internet connection)
- A random identifier created by the App when it is installed. It is used **only** so our server can apply rate limits (a cap on how many requests one install, and one IP address, can make per minute and per day) and limit abuse. It is not linked to your name, Apple ID or advertising identifier.

Our server does **not** check, store or know your credit balance or your purchases. It does not save the install ID or your IP address in a database or in its logs; rate-limit counters are kept only temporarily in the server's working memory and are discarded automatically.

### 1.4 Purchases

Hirewise sells consumable credit packs through **Apple In-App Purchase**. Payment is handled entirely by Apple; we never see your card or billing details.

The App uses Apple's StoreKit directly on your iPhone to show prices and complete purchases. When a purchase completes, the App adds the credits to the balance stored **on your device only**, and remembers the transaction ID on the device so it is never counted twice. No third-party purchase-management service is used, and **nothing about your purchases is sent to our server**. Apple gives us aggregate sales reports in App Store Connect, which do not identify you to us.

### 1.5 What We Do NOT Collect

- No account, sign-up or login. Hirewise 1.0 does not ask for an email address or password.
- No access to your contacts, photos, camera, microphone or location. The App does not request these permissions.
- No advertising, no advertising identifier (IDFA) and no tracking across other apps or websites.
- No third-party purchase-management services.
- No analytics or third-party crash-reporting SDKs. If you have chosen to share analytics with developers in iOS Settings, Apple may give us anonymous crash reports and usage statistics under Apple's own policy.

---

## 2. How We Use Information

We use the information above only to:

- Generate your tailored resume
- Keep your credit balance on your device and add the credits you buy
- Keep the service working and protect it against abuse, fraud and overuse
- Answer your support emails

We do **not** sell your information, share it for advertising, or use your resume text to build a profile about you. We do not use your resume text to train AI models.

---

## 3. Third Parties

Your information is shared only with the following service providers, and only for the purposes described:

- **Vercel** (Vercel Inc.) hosts our server, which receives your request, passes it to the AI provider and returns the result. [Vercel Privacy Policy](https://vercel.com/legal/privacy-policy)
- **Anthropic** (Anthropic PBC, maker of the Claude AI models) is our AI provider. It receives your resume details and job description in order to write the tailored resume. We use Anthropic's paid commercial API. Under those terms, the text you send is not used to train Anthropic's models, and Anthropic may keep it for a limited period (normally up to 30 days) to detect abuse before deleting it. [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy)
- **Apple** processes In-App Purchases and App Store distribution. [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

These companies may process data in the United States or other countries outside India. We may also disclose information if required by law.

<!-- OWNER: the AI provider is Anthropic (Claude), the same as Unvarnished. If the server switches provider, update this section and the consent screen first. -->

---

## 4. Storage and Retention

- **Your resume and job description text on our server:** processed in memory to complete your request and **not stored** after the response is sent. We do not keep a copy of your resume or the generated result.
- **Server logs:** our server's own logs record only which endpoint was called, the app name, whether the request succeeded and how long it took. They do not contain your resume or job description text, your IP address or the install ID. Our hosting provider, Vercel, may keep its own standard request logs, which can include IP addresses, for security and operations. These logs are kept for **at most 30 days**.
- **Rate-limit counters:** the install ID and IP address are held only in the server's temporary memory to apply rate limits, and are never written to a database or log.
- **Credit records:** kept **on your device only**. Our server does not store credits, balances or purchase transaction IDs.
- **AI provider:** may keep request data for a limited period for abuse monitoring under its own terms, as described in section 3.
- **Purchase records:** kept by Apple under Apple's own policy.
- **On your device:** kept until you delete it or uninstall the App.

---

## 5. Deleting Your Data

- **On your device:** in **Settings → Delete all data**, you can remove your saved details, job descriptions, generated resumes, their PDFs, your consent choice and the install ID. Your credit balance is kept so paid credits are not lost. Uninstalling Hirewise deletes everything the App stored, including your credit balance; unused credits cannot be recovered after that. PDFs you saved or shared elsewhere (for example to the Files app or email) must be deleted there.
- **On our server:** we do not keep your resume text, credits or purchase records, and logs are deleted automatically within 30 days. If you want logs about your use deleted sooner, email us with the approximate date and time you used the App and we will delete matching records where we can.
- **Purchase records:** kept by Apple under Apple's policy. We hold no purchase records of our own.

Hirewise 1.0 has no accounts, so there is no account to delete.

---

## 6. Your Choices and Rights

- You choose what text to enter and whether to upload it.
- You can decline the consent screen; no text is uploaded.
- You can ask us what information we hold about you, ask us to correct it, or ask us to delete it, by emailing us. Because we do not keep your resume text, in most cases we will hold little or nothing.

---

## 7. Security

Data sent between the App, our server and the AI provider is encrypted in transit using HTTPS. Access to our server and logs is restricted to the developer. No method of transmission or storage is completely secure, but we keep the data we handle to a minimum.

---

## 8. Children's Privacy

Hirewise is a job-application tool and is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has sent us personal information, email us and we will delete any record of it.

---

## 9. Changes to This Policy

We may update this policy, for example when we add features or change service providers. The "Last updated" date at the top will change, and significant changes will be shown in the App or in the App Store listing. If a change affects how your resume text is handled, we will ask for your consent again in the App before uploading.

---

## 10. Contact

Questions or requests about privacy:

- **Email:** asquare938@gmail.com
- **Subject:** Hirewise Privacy
- **Developer:** Akash Sinha, India

See also: [Hirewise Support](support.html?file=hirewise_support.md)

<!--
APP STORE PRIVACY LABEL (suggested answers for App Store Connect > App Privacy), checked against ResumeMaker branch ios-mvp
and tattvam-ai-server:

Tracking: NO. No IDFA, no ad SDKs, no data shared with data brokers. No App Tracking Transparency prompt needed.

Data collected (data that leaves the device and reaches the developer or its service providers):

1. User Content > Other User Content: YES (resume details and job description text sent to /api/resume/tailor; the generated resume).
   Purpose: App Functionality.  Linked: NO.  Tracking: NO.

2. Contact Info > Name, Email Address, Phone Number: declare to be safe (YES), Purpose: App Functionality, Linked: NO, Tracking: NO.
   Reason: in form mode the app strips contact fields before sending (src/lib/profile.js buildDetailsText omits
   contact.name/email/phone/location/links; they are added to the PDF on device). But in "Paste my resume" mode the pasted
   text is sent as-is and normally contains name, email and phone. If paste mode is removed or contact lines are stripped
   from pasted text, this row can be dropped.

3. Identifiers > Device ID: YES (the app-generated random install ID, sent as X-Install-Id).
   Purpose: App Functionality (used only for server-side rate limiting / abuse prevention; held in memory, not stored).
   Linked: YES (marked linked to be cautious).  Tracking: NO.

4. Purchases > Purchase History: NOT collected. Purchases use expo-iap (StoreKit 2) on device; credits and credited
   transaction IDs are stored only on the device. Nothing purchase-related is sent to the server, and the server has
   no credit check (it only rate-limits by install ID and IP).

5. Diagnostics: NO (no crash-reporting or analytics SDK). Apple's own opt-in crash data does not need to be declared.
   The IP address is used only for in-memory rate limiting and may appear in the hosting provider's request logs (<=30 days);
   it is not used to derive location and does not need its own row.

Not collected: Location, Contacts, Health, Financial Info (Apple handles payment), Purchases, Sensitive Info,
Browsing/Search History, Usage Data, Photos/Videos, Audio, Advertising Data.

Privacy Policy URL: https://ulteridon.github.io/privacy-poilicies/policy.html?file=hirewise_privacy_policy.md
Support URL:        https://ulteridon.github.io/privacy-poilicies/support.html?file=hirewise_support.md
-->
