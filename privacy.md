---
layout: default
title: Privacy Policy - Car Satei Lab Auto Poster
---

# Privacy Policy — Car Satei Lab Auto Poster (車査定ラボ SNS Auto Posting Service)

**Effective date**: 2026-04-28
**Last updated**: 2026-05-01
**Operator**: 株式会社エメラルドオーシャン (the "Operator")
**App name**: **"Car Satei Lab Auto Poster"** (registered name on TikTok for Developers Portal) / 車査定ラボ SNS Auto Posting Service (the "Service" / the "App")

---

## 1. Scope of This Policy

This Privacy Policy applies specifically to the application registered as **"Car Satei Lab Auto Poster"** on the TikTok for Developers Portal (and on Meta for Developers, Google Cloud Console, and the X Developer Portal under the same product line). It describes how the Operator collects, uses, stores, and discloses information in connection with the operation of **"Car Satei Lab Auto Poster"** (the "Service" / the "App"). The App performs automated posting of short-form video content to multiple social media platforms on behalf of authorized Brand Account holders (hereafter "Clients").

The Service operates in a **multi-tenant authorization-delegation model**: Clients grant the Operator the necessary platform permissions, and the Operator publishes content on their behalf. The Operator is the **data processor**; each Client remains the **data controller** for their own brand account data.

This Policy applies to all Clients, end users of the Service, and any individuals whose personal data is processed via the Service.

---

## 2. Information We Access via TikTok API

**"Car Satei Lab Auto Poster"** accesses the following from TikTok via the official TikTok for Developers APIs:

- **TikTok account ID and basic profile** (via `user.info.basic` scope) — display name, avatar, open_id of the Client's authorized TikTok account
- **Permission to upload videos** (via `video.upload` scope) — used to upload Client-approved short-form video content
- **Permission to publish videos** (via `video.publish` scope) — used to publish the uploaded content to the Client's authorized TikTok account

All data is accessed **only with explicit Client authorization** via the TikTok OAuth flow. Tokens are stored encrypted on the Operator's local machine (macOS FileVault, file mode 0600) and are revocable by the Client at any time.

---

## 3. Information from Other Platforms

In addition to TikTok, **"Car Satei Lab Auto Poster"** processes equivalent authorization from:

- **Meta** (Facebook Page Token, Instagram Business Account ID) via `instagram_content_publish`, `pages_manage_posts`, `pages_read_engagement`, `business_management`, `instagram_basic`
- **YouTube** (OAuth Refresh Token) via YouTube Data API v3 scopes `youtube.upload`, `youtube`
- **X / Twitter** (OAuth tokens) via v2 API write scopes

---

## 4. Information We Do **NOT** Collect

**"Car Satei Lab Auto Poster"** does **not** collect or process:

- Personal data of viewers, followers, or any other end users of the platforms
- Comments, direct messages, or follower lists from the Client's accounts (insights are aggregate-level only)
- Watch-time data of identified individuals
- Cookies, advertising identifiers, or cross-site tracking pixels
- Biometric, health, financial, or government-issued identification data
- Children's personal data (Service is for content creators 18+ targeting general audiences)

---

## 5. Purpose of Processing

We process the information described above solely for:

- Generating and publishing content to the Client's authorized platform accounts via **"Car Satei Lab Auto Poster"**
- Maintaining the technical operation of the Service (token refresh, scheduling, error reporting)
- Producing aggregated performance reports to the Client
- Complying with platform Terms of Service and applicable laws (景品表示法, GDPR principles, CCPA opt-out)

We do **not** sell, rent, or share the data with third parties for marketing or advertising purposes.

---

## 6. Data Storage and Security

| Data type | Storage location | Encryption | Retention |
|---|---|---|---|
| OAuth tokens | Operator's local Mac, file mode `0600` | macOS FileVault (at-rest); TLS 1.2+ (in-transit) | Until Client revokes or platform expires |
| Generated videos & captions | Operator's local Mac, project subdirectory | macOS FileVault | 90 days, then archived offline; or earlier upon Client request |
| Post metadata (insights) | Operator's local Mac CSV/JSON; optionally Google Sheets per Client | TLS in transit; Sheets at-rest by Google | 24 months or per Client agreement |
| Service logs (no PII) | Operator's local Mac log files | macOS FileVault | 30 days rolling |

The Operator does not transmit Client tokens or generated content to any cloud service except the official APIs of the target platforms (Meta Graph API, TikTok Content Posting API, YouTube Data API, X API).

---

## 7. Client and User Rights

### 7.1 Right to revoke authorization

A Client may revoke the Service's access to their platform account at any time:

- **TikTok**: Settings → Manage Apps → Revoke "Car Satei Lab Auto Poster"
- **Meta**: Settings → Business Integrations → Remove access for "car-satei-lab-i"
- **YouTube/Google**: myaccount.google.com → Security → Third-party apps with account access → Remove
- **X**: Settings → Security and account access → Apps and sessions → Revoke

Upon revocation, **"Car Satei Lab Auto Poster"** will stop posting to that account on the next scheduled run.

### 7.2 Right to data deletion

A Client may request deletion of all stored data via the procedure documented in `data_deletion.md`. The Operator will delete:

- All OAuth tokens for the Client
- All generated videos, captions, and metadata associated with the Client
- All log entries identifying the Client

within seven (7) business days of a verified deletion request, and confirm in writing.

### 7.3 Right to access and correction

Clients may request a copy of all data we hold about them and request correction of inaccurate data, by emailing the contact below.

---

## 8. International Transfers

Data may be transferred to and processed in jurisdictions where the Operator's local environment or the platforms' servers are located, including the United States, the European Union, and Japan. Where required by law, appropriate safeguards (Standard Contractual Clauses or equivalent) are in place.

---

## 9. Children's Privacy

**"Car Satei Lab Auto Poster"** is operated for and by adults. Content does not target children under 16, and the Service does not knowingly process the personal data of children. If we learn that we have processed such data, we will delete it promptly.

---

## 10. Compliance with Platform Policies

The Operator commits to:

- TikTok Developer Terms of Service and Community Guidelines
- Meta Platform Terms (Developer Policies, Platform Terms)
- YouTube API Services Terms of Service and YouTube Community Guidelines
- X Developer Agreement and Policy
- Japanese Act on the Improper Use of Premiums and Misleading Representation (景品表示法)

---

## 11. Changes to This Policy

We may update this Policy from time to time. Material changes will be communicated to active Clients by email at least 14 days before taking effect. The "Last updated" date at the top of this document indicates the current version.

---

## 12. Contact

For privacy or data protection questions regarding **"Car Satei Lab Auto Poster"**, including data access, correction, or deletion requests:

- **App name**: Car Satei Lab Auto Poster (車査定ラボ SNS Auto Posting Service)
- **Email**: ikeda.naoya.1220@gmail.com
- **Postal address**: 大阪府堺市西区鳳中町9丁目344-57
- **Operator**: 株式会社エメラルドオーシャン

Response target: within 7 business days.
