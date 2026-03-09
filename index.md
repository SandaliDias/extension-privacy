# Privacy Policy - AURA Interaction Tracker

**Last updated:** March 8, 2026  
**Effective date:** March 8, 2026

This Privacy Policy explains how the AURA Interaction Tracker Chrome extension ("Extension", "we", "our", "us") collects, uses, stores, and shares data.

## 1. Single Purpose

The Extension has one user-facing purpose: to provide accessibility-related UI adaptation and insights based on your interaction patterns.

We do not use collected data for advertising, ad targeting, data brokerage, or unrelated profiling.

## 2. Data We Collect

We collect data only for the purpose above, and only after required consent.

### 2.1 Account and Profile Data

When you register or sign in, we collect:

- Email address
- Password (stored as a hash; plain-text passwords are not stored)
- Full name
- Age
- Gender

### 2.2 Authentication and Local Extension State

We store the following in extension/browser storage:

- Authentication token
- User ID
- Consent status
- Session/login state

### 2.3 Web Browsing Activity and Interaction Data

After you provide consent during registration and while you are logged in, we collect:

- Page metadata: URL, page title, referrer, viewport size
- Click interaction metadata: click position (x, y), element type, element ID/class
- A short visible text snippet from the clicked element (up to 100 characters)
- Mouse movement, scroll position, zoom events
- Touch events (for example, swipe or pinch)
- Keyboard event metadata where character content is not collected
- Character keys are masked as `[CHAR]` before storage/transmission
- Non-character keys (for example, Enter, Tab, Escape) may be logged as key type only

We do not intentionally collect:

- Password values
- Payment card numbers
- Full page content
- Screenshots
- Full form input text

### 2.4 Derived and Aggregated Metrics

From event streams, we compute metrics such as:

- Click count, click intervals, dwell time, misclick rate
- Rage-click patterns
- Scroll speed and zoom frequency
- Domain and route-level behavior metrics

### 2.5 Onboarding and Assessment Data

If you complete onboarding or assessment flows, we collect resulting scores/profile outputs (for example, impairment profile and related accessibility tuning data).

## 3. How We Use Data

We use data to:

- Authenticate users and keep sessions active
- Generate accessibility-oriented interaction summaries
- Personalize UI adaptation settings
- Maintain, secure, and improve Extension reliability (using aggregated or de-identified data where possible)

We do not sell or rent user data.

## 4. Data Sharing and Recipients

We share data only with the recipients below:

- **AURA backend API** (`extension-backend-theta.vercel.app`) to store accounts, preferences, onboarding results, and interaction batches.
- **Vercel, Inc.** as infrastructure host for backend services.
- **Legal/security disclosures** when required by law, court order, or to protect rights and security.

Current recipient list does not include advertisers or data brokers.
If we add a new external processor, we will update this policy before sharing data with that processor.

## 5. Consent and User Controls

- Before account creation, the Extension presents in-product disclosure and requires an affirmative user action.
- Registration is available only after consent to the disclosed data use.
- You can withdraw consent by logging out and requesting account deletion.
- You can request account/data deletion by contacting us (see Contact section).
- Uninstalling removes locally stored extension data.

## 6. Data Retention

Unless a longer period is required by law:

- Account/profile data: retained while account is active, then deleted within 30 days of confirmed deletion request.
- Raw interaction event batches: retained up to 90 days.
- Derived/aggregated interaction metrics: retained up to 12 months.
- Onboarding/assessment outputs: retained up to 12 months or until account deletion, whichever comes first.
- Security and audit logs: retained up to 30 days.

## 7. Security

We use reasonable security controls, including:

- HTTPS/TLS in transit
- Password hashing
- Access controls for backend systems

No method of transmission or storage is 100% secure, but we continuously work to protect user data.

## 8. Children's Privacy

The Extension is not intended for children under 18. We do not knowingly collect personal data from children.

## 9. Changes to This Policy

We may update this policy from time to time. Material changes will be reflected by updating the "Last updated" date and, where appropriate, via in-extension notice or email.

## 10. Chrome Web Store User Data Commitments

We commit to the Chrome Web Store User Data Policy and Limited Use requirements:

- Data is used only for the Extension's stated single purpose.
- Data is not used or transferred for advertising or ad targeting.
- Data is not sold.
- Access to user data is limited to what is necessary to provide, secure, and maintain the service.

## 11. Contact

For privacy questions, access/deletion requests, or policy concerns:

- **Email:** ssd.dias29@gmail.com
