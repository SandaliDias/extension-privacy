# Privacy Policy - AURA

**Last updated:** May 2, 2026  
**Effective date:** May 2, 2026

This Privacy Policy explains how the AURA Chrome extension ("AURA", "Extension", "we", "our", "us") collects, uses, stores, and shares data when you use the extension and related AURA services.

## 1. Single Purpose

AURA has one user-facing purpose: to provide accessibility-oriented personalization and related onboarding, profile generation, and interface adaptation based on your consented interaction patterns and onboarding results.

We do not use user data for advertising, ad targeting, data brokerage, or unrelated profiling.

## 2. Data We Collect

We collect only the data reasonably necessary to provide AURA's stated purpose.

### 2.1 Account and Registration Data

When you create an account, sign in, or verify your email, we may collect:

- Email address
- Password (stored as a hash; we do not store your plain-text password)
- Full name
- Age
- Gender
- Email verification status

### 2.2 Extension and Local Browser Storage Data

We store certain data in Chrome extension storage on your device, such as:

- Authentication token
- User ID
- Consent status
- Registration and onboarding state
- Basic user profile data (such as name and email)
- Onboarding completion state
- Generated personalization profiles used by AURA features

### 2.3 Onboarding and Assessment Data

If you use the AURA onboarding experience, we may collect and generate:

- Onboarding session records
- Assessment results and scores
- Impairment or accessibility profile outputs
- Personalized profile data derived from onboarding results

### 2.4 Interaction Signals and Web Browsing Activity

After you affirmatively provide consent in the extension and while you are logged in, AURA may observe interaction signals from webpages you visit in order to provide its accessibility-related personalization features.

These signals may include:

- Full page URL processed by the extension to understand page context
- Viewport and page geometry information
- Click metadata such as element tag, click position, and button type
- Mouse movement, scroll, dwell, drag/drop, zoom, touch, swipe, and pinch interaction metadata
- Keyboard event metadata where character keys are masked as `[CHAR]`
- Non-character key metadata such as Enter, Tab, Escape, or shortcut usage when relevant to the feature

For the publishable AURA extension package, AURA is designed to transmit aggregated interaction batches for backend storage and personalization workflows. Those aggregated batches include sanitized page context such as domain and route rather than full page content.

### 2.5 Data We Do Not Intentionally Collect as Part of the Publishable Extension Flow

We do not intentionally collect or transmit the following as part of the publishable AURA extension flow:

- Plain-text passwords
- Full form input text
- Payment card numbers
- Full page content
- Screenshots
- Clicked element text snippets
- Page titles or referrers for the publishable package's interaction pipeline

### 2.6 Derived and Aggregated Data

We may derive or generate:

- Aggregated interaction metrics such as click counts, dwell time, misclick rate, rage-click patterns, zoom frequency, and scroll speed
- Sanitized page-context summaries such as domain and route-level behavior metrics
- Personalized accessibility or adaptation profiles
- Profile-feedback or profile-change records

## 3. How We Use Data

We use data to:

- Create and manage accounts
- Authenticate users and maintain signed-in sessions
- Verify email ownership when verification is enabled
- Deliver and save onboarding and assessment results
- Generate accessibility-related personalization profiles
- Process consented interaction signals into aggregated metrics
- Improve, secure, maintain, and troubleshoot AURA services
- Prevent abuse, fraud, or unauthorized access

We do not sell or rent user data.

## 4. How We Share Data and With Whom

We share user data only as necessary to provide AURA's single purpose, comply with law, or protect security.

### 4.1 AURA Service Providers and Related Services

We may share data with the following recipients:

- **AURA backend services** hosted at `https://extension-backend-theta.vercel.app` to manage accounts, consent status, onboarding records, deletion requests, and interaction-related backend storage.
- **AURA onboarding web application** hosted at `https://onboarding-frontend-psi.vercel.app`. When you launch onboarding from the extension, AURA provides the onboarding app with the information needed to associate the onboarding flow with your account, such as your user ID and authentication token.
- **AURA ML and personalization services** hosted at `https://mlengine.auraui.org` to generate or refresh personalized profiles, process onboarding-derived profile inputs, and process profile feedback. Depending on service configuration, these services may also receive aggregated interaction metrics needed for personalization.
- **Infrastructure and storage providers** used to operate AURA services, including hosting and database providers such as Vercel, Inc. and MongoDB Atlas / MongoDB, Inc., to the extent needed to host, store, and secure AURA data.

### 4.2 Legal, Security, and Business Transfers

We may also disclose data:

- When required by applicable law, regulation, legal process, or enforceable government request
- To investigate, prevent, or address fraud, abuse, security incidents, or technical issues
- In connection with a merger, acquisition, or asset transfer, subject to applicable legal requirements

We do not share user data with advertisers or data brokers.

## 5. Consent and User Controls

- You may create an account before granting interaction-tracking consent.
- AURA requires an affirmative consent action in the extension before interaction tracking for personalization is enabled.
- AURA's interaction pipeline is intended to store and transmit interaction-derived data for your account only after the relevant setup flow, including onboarding completion, is in place.
- You can log out at any time from within the extension.
- You can permanently delete your account from within the extension using the delete-account feature, or by contacting us.
- Uninstalling the extension removes extension data stored locally in your browser, but it does not automatically delete your backend account unless you also delete the account.

## 6. Data Retention

We retain data only for as long as necessary for the purposes described in this policy, unless a longer retention period is required by law.

Current retention targets for the AURA system include:

- **Account and profile data:** retained while your account is active; if you delete your account in-product, deletion is intended to occur promptly, and manual deletion requests are handled as soon as reasonably practicable.
- **Transient or raw interaction records, where stored by a backend flow:** up to 30 days.
- **Aggregated interaction batches:** up to 2 years.
- **Onboarding session records and onboarding result records:** up to 1 year.
- **Operational, security, and troubleshooting logs:** retained only as needed for security, abuse prevention, debugging, and legal compliance.

Retention periods may change if the product changes or if we are required to retain certain data for legal or security reasons.

## 7. Security

We use reasonable administrative, technical, and organizational safeguards to protect user data, including:

- HTTPS/TLS for data in transit
- Password hashing
- Access controls for AURA systems and services
- Account and session validation mechanisms

No method of transmission or storage is completely secure, but we work to reduce risk and protect user data appropriately.

## 8. Children's Privacy

AURA is not intended for children under 18, and we do not knowingly provide accounts for or intentionally collect personal data from children under 18.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last updated" date and may provide additional notice through the extension, related services, or email where appropriate.

## 10. Chrome Web Store User Data Commitments

We intend to comply with the Chrome Web Store User Data Policy and Limited Use requirements. In particular:

- We use personal or sensitive user data only for AURA's stated single purpose and closely related user-facing functionality.
- We do not use or transfer user data for advertising, ad targeting, or data brokerage.
- We do not sell user data.
- We do not allow humans to read personal or sensitive user data except when necessary for a specific user-requested support action, for security purposes, to comply with law, or when working with aggregated or de-identified information for internal operations.

## 11. Contact

For privacy questions, deletion requests, or other data-protection concerns, contact:

- **Email:** ssd.dias29@gmail.com
