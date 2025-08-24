# Privacy Policy

**Effective date:** August 24, 2025

CleanTrail ("we", "our", or "us") is a browser extension designed to help users protect their privacy while browsing the web. This Privacy Policy explains what information the extension accesses, how it is used, and the choices available to users.

We design CleanTrail with privacy-first principles: the extension's core protections — cookie cleanup, tracker blocking, and anti-fingerprinting measures — run **locally on your device**. Backend services are used for subscription management, phishing checks, community tracker list updates, and encrypted sync for Pro+ users. Remote services are never used to execute arbitrary code inside your browser.

---

## Information We Collect

CleanTrail may access the following types of information while you use the extension:

* **Web history (URLs visited):** Access to active tab URLs and requests is used locally to detect trackers, apply cleanup rules, and check sites against phishing/malware feeds (e.g., Google Web Risk). We do not sell this data.

* **User activity:** This covers network request metadata and extension actions (e.g., which requests were blocked, fingerprinting attempts detected, and cleanup operations you trigger). This data is used to apply protections, build local analytics (e.g., "Top blocked trackers"), and present in-extension UI.

* **Tracker blocking behavior:** When you block, allow, or promote a domain (for example promoting a domain from a pending list to blocked), CleanTrail records these choices **locally** to remember and apply your preferences. If you opt into Smart Sync / community feedback, anonymized and aggregated signals derived from these actions *may* be uploaded (with your consent) to improve community-sourced tracker lists. Opt-in can be disabled at any time.

* **Account & subscription info (Pro and Pro+ only):** If you activate Pro or Pro+, we store your email and a subscription activation token to manage your license. Payments are processed by Stripe — CleanTrail does not see or store full credit card numbers.

* **Sync data (Pro+ users who enable encrypted sync):** Trusted sites, profiles, and settings can be synced across devices. Before leaving your device, this data is encrypted client-side with a key derived from your passphrase so our servers cannot read your synced content.

CleanTrail does **not** collect or request personal communications (emails, chats), health data, or precise GPS location.

---

## How We Use Information

We use collected information to:

* Provide on-device protections: block trackers, delete cookies and site data, and mitigate fingerprinting.
* Apply and remember your blocking preferences and per-site overrides.
* Display useful analytics in the extension UI (e.g., number of trackers blocked, top trackers) using locally-stored aggregates.
* Manage subscriptions and license activations via our backend.
* Offer phishing checks via Google Web Risk.
* Improve detection models: if you opt into Smart Sync / feedback, anonymized signals may be used to improve community tracker lists.

We never sell personal data.

---

## Data Sharing and Third Parties

* **No sale of personal data.**
* **Google Web Risk API:** used to check URLs against Google’s unsafe site lists for phishing/malware protection. Only URL checks and threat verdicts are exchanged with Google.
* **Stripe:** payment processing for subscriptions. Stripe handles card data according to their privacy/security policies. CleanTrail receives only transaction metadata necessary to confirm and manage subscriptions.
* **Our backend:** required for Pro activations, subscription validation, tracker list updates, phishing protection, and encrypted sync. Sync data is encrypted before upload; activation metadata is limited to what’s needed to manage accounts.
* **Other service providers:** we may use analytics or hosting services in anonymized, aggregate form to operate and maintain the service. These providers are contractually required to only process data for the purposes we specify.

---

## Data Retention

* Local web history and activity logs remain on your device and are removed when you clear data in the extension settings or uninstall CleanTrail.
* Pro account and activation data are retained while your subscription is active and for a short period afterward to support account management and legal obligations.
* Encrypted sync blobs are retained until you delete them or your account; because they are encrypted client-side, we cannot access their contents.

---

## Your Choices

* Use CleanTrail in base mode without enabling Pro features.
* Opt in or out of Smart Sync / community feedback at any time (opt-in is off by default).
* Disable phishing checks or any optional remote features in settings.
* Clear local extension data or uninstall the extension to remove locally-stored information.
* Request deletion of your Pro account or synced data by contacting us (see below).

---

## Security

We use industry-standard technical and organizational measures to protect data, including TLS for network communications and encryption for client-side sync. While we take reasonable steps to secure data, no system is completely immune to risk. If a security incident impacts personal data, we will notify affected users as required by law.

---

## Children

CleanTrail is intended for users aged 13 and older. We do not knowingly collect personal information from children under 13. If we learn we have collected data from a child under 13 without parental consent, we will promptly delete it.

---

## Changes to this Policy

We may update this Privacy Policy to reflect changes in our practices or legal requirements. We will post the updated policy in this repository and highlight material changes in the extension changelog.

---

## Contact Us

If you have questions or want to request data deletion, contact us at **[businesscleantrail@outlook.com](mailto:businesscleantrail@outlook.com)**.

*Last updated: August 24, 2025*

