# Privacy Policy for AIHub Studio

**Effective Date:** October 31, 2026  
**Developer:** Raas Weblink  
**Application:** AIHub Studio - AI Workspace (`com.raas.aihub.studio`)  
**Contact:** raseshrehl@gmail.com

---

## Overview

Welcome to **AIHub Studio** ("we", "our", or "the app", package name: `com.raas.aihub.studio`), developed by **Raas Weblink**. We are dedicated to respecting and protecting your privacy. AIHub Studio is designed as an on-device, privacy-first productivity suite and AI workspace. 

This Privacy Policy explains how our application operates, how user data is handled, and our compliance with Google Play Developer Program Policies, including the **AI-Generated Content Policy**.

---

## 1. Information We Collect and Store

**AIHub Studio does not collect, transmit, sell, or harvest any personal information.**

### a. On-Device Local Storage Only
All user-generated content, configurations, and settings remain strictly stored on your local device via local Android storage (`SharedPreferences`):
* **Chat Transcripts & History:** Saved locally on your device.
* **Code & Writing Snippets:** Processed and stored locally.
* **Prompt Vault & Bookmarks:** Saved locally on your device.
* **UI Preferences:** Theme mode (dark/light) and accent color selections are stored locally.

We do not operate any intermediary proprietary database or server that collects or stores your prompts, outputs, or device identifiers.

### b. API Keys (Bring Your Own Key - BYOK)
If you choose to input personal API keys (such as Google Gemini or OpenAI API keys):
* They are stored strictly on your local device.
* They are never transmitted to our servers or any unauthorized third party.
* They are transmitted directly from your device to the respective official API endpoints (Google or OpenAI) solely to fulfill your requested prompts.

---

## 2. Device Permissions Usage

AIHub Studio requests minimal Android permissions necessary for its intended core features:
* **Internet Access (`android.permission.INTERNET`):** Required exclusively to:
  1. Communicate directly with AI provider APIs (e.g., Google Gemini, OpenAI, Pollinations) to generate requested text, code, or images.
  2. Load typography from Google Fonts.
  3. Allow users to open external links to productivity tools featured in the curated directory.

The app does **not** request access to your device location, contacts, microphone, camera, or external storage files.

---

## 3. Generative AI Safety & Content Moderation

In accordance with Google Play's **AI-Generated Content Policy** and **Sexual Content and Profanity Policy**:

* **Automated Guardrails & Input Moderation:** AIHub Studio implements automated client-side content moderation guardrails (`ContentFilterService`). Any user prompt requesting sexual content, nudity, sexually suggestive imagery, profanity, vulgarity, hate speech, or violence is proactively intercepted and blocked before any AI generation request is initiated.
* **Safe-Mode Enforcement:** Image generation requests enforce strict safety parameters (`safe=true`) and positive safety tags to ensure visual output remains safe for work and family-friendly.
* **User Reporting Mechanism:** AIHub Studio includes an accessible in-app reporting dialog across all AI tools, enabling users to flag any inappropriate, offensive, or policy-violating AI-generated content immediately.

---

## 4. Third-Party Services & Links

When utilizing AI features or following external directory links, you may interact with third-party services:
* **Google Gemini API / OpenAI API:** Interactions are governed by Google's Privacy Policy and OpenAI's Privacy Policy.
* **Pollinations API:** Visual diffusion requests are processed through Pollinations with safe-mode enforcement.
* **External Directory Links:** The app features a curated directory of external AI tools and platforms. We do not control and are not responsible for the privacy practices, content, or policies of external third-party websites.

---

## 5. Children's Privacy

AIHub Studio is intended for general audiences aged 18 and older. We do not knowingly collect, solicit, or maintain personal information from children under the age of 13 (or under 18).

---

## 6. Data Retention, Control, and Deletion

Because AIHub Studio does not store user data on external servers, **you have 100% control over your data**:
* You can clear all saved chat histories, vault prompts, and API keys directly inside the app settings.
* You can instantly delete all local data by clearing the app's cache and storage in your Android system settings (`Settings > Apps > AIHub Studio > Storage > Clear Data`), or by uninstalling the app.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our app features or regulatory requirements. Any updates will be published immediately to this repository with an updated "Effective Date".

---

## 8. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or our data practices, please contact us:

* **Developer:** Raas Weblink
* **Contact Name:** Rashesh Rehi
* **Email:** [raseshrehl@gmail.com](mailto:raseshrehl@gmail.com)
* **GitHub Repository:** [https://github.com/rashesh-rehi252/aihub-privacy-policy](https://github.com/rashesh-rehi252/aihub-privacy-policy)
