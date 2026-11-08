---
title: Privacy Policy
permalink: /privacy-en/
lang: en
---

# Pear Health Privacy Policy

[中文](../privacy/)

We try to explain in plain language how Pear Health handles your information. If you have questions, feel free to write to us anytime.

## 1. Who we are

Pear Health is an app that helps you organize and understand your lab reports. It is operated by Dolores Education Inc. We handle your information in accordance with applicable laws.

## 2. What we collect

- **Sign-in information**: you can use "Sign in with Apple" or sign in with an email code. With Apple, Apple gives us an account identifier; if you choose to share it, we also receive an email address, which may be Apple's relay email. With email, we keep the address you enter and send it a 6-digit code valid for 10 minutes; there is no password. Sign-in is handled by our identity provider, Supabase.
- **Lab reports**: you can upload a PDF or a photo of a lab report. The original file is stored in private cloud storage. Recognition runs by default on your phone, and the recognized results (analyte name, value, unit, reference range, test date) are stored in our database. When on-device recognition is uncertain, the lab-table regions of the report are sent to our cloud AI provider for review after names, ID numbers and other personal details are automatically masked (see section 5).
- **Supplement label photos**: label scanning is not available yet, and we do not collect label photos. We will update this policy before it becomes available.
- **Plans and reminders**: plan data such as retest dates and reminder settings is stored in our database.
- **Care circle**: you can invite family members or caregivers with an invite link that is valid for 72 hours. Invited people only see what you choose to share, and you can revoke access at any time.

## 3. How we use it

We use the above information only to provide the service: keeping your reports and recognized results, generating plans and reminders, and letting the people you invite see what you choose to share. We do not use this information for advertising.

## 4. Apple Health data

With your permission, Pear Health reads sleep, heart rate, and step count on your phone, solely for the "Today" view on the home screen. This data is **not uploaded to our servers**, not used for advertising, not sold, and not shared with any third party. You can turn it off anytime in iOS Settings → Health → Data Access & Devices.

## 5. Where it is stored and who processes it for us

- Lab report originals are stored in private cloud storage provided by Supabase, located in the eastern United States.
- Our database is also hosted by Supabase in the eastern United States.
- Backend services are hosted on Fly.io, located in the United States. All traffic between the app and our servers is encrypted over HTTPS.
- Sign-in is handled by Apple and Supabase. Sign-in code emails are sent through Resend, which receives only the recipient address and the code email itself.
- **Cloud AI review** (provided by Anthropic, United States): used only for lab report image recognition. When on-device recognition is uncertain, the app sends the lab-table regions of the report (with names, ID numbers and other personal details automatically masked) to Anthropic's Claude model for review and receives only the recognized results; Anthropic does not use this content to train models. By registering for and using Pear Health you agree to this processing (effective November 8, 2026). Supplement label photos and full-text cloud recognition of reports remain disabled; we will update this policy before enabling them.

## 6. Your choices and rights

- **Export**: you can export all of your data inside the app (a ZIP file); the download link is valid for 15 minutes.
- **Delete your account**: you can request account deletion inside the app. There is a 7-day cooling-off period during which you can cancel the request. After that, the account and its data are deleted.
- **Withdraw consent**: you can contact us at any time to stop cloud review (recognition then runs only on your phone), revoke care circle invites, and turn off Apple Health access.

## 7. How long we keep it

We keep your data until you delete your account. After deletion, for safety we retain operation logs (what action was performed and when, without report contents) for up to 400 days.

## 8. What we do not do

- We do not show ads;
- We do not integrate third-party advertising or tracking SDKs;
- We do not sell personal information.

## 9. Minors

Pear Health is intended for users aged 18 and above.

## 10. Changes to this policy

If this policy changes, we will update this page and the effective date.

## 11. Contact us

For privacy questions and deletion requests, email kova@pearlab.ai.

Effective date: November 8, 2026
