# Privacy Policy for AngleMate
Last updated: October 9, 2026

This policy explains how **Slava Bell** ("we", "us", or "our") handles information when you use AngleMate for Android or iOS. AngleMate provides bubble level, camera alignment, and screen ruler tools.

Privacy contact: **[sb@iambell.com](mailto:sb@iambell.com)**.

## 1. Measurements, sensors, and camera access
AngleMate uses your device's motion and orientation readings, including accelerometer readings, to calculate angles and display level and alignment information. These readings and the resulting measurements are processed on your device. We do not upload them or include them in Analytics or error reports. The app does not maintain a persistent measurement history.

The Laser Level tool requests camera permission to display a live rear-camera preview with an alignment guide. The preview stays on your device. AngleMate does not record, save, or upload photos or video from it. Camera access stops when the preview is closed or the app goes into the background.

The flashlight feature uses the device's camera light where available. You can deny or revoke camera permission through your device's app settings; the camera preview will then be unavailable.

## 2. Local settings and accounts
AngleMate saves preferences such as measurement precision, smoothing, sound, display options, ruler calibration, and your optional-sharing choices in local app storage. The app does not operate a cloud synchronization service for these settings.

Your operating system's backup and device-transfer services may include app settings, depending on your device configuration. These services are controlled by your operating system and account settings.

AngleMate does not require an account and does not ask for your name, email address, or phone number to use its tools. It does not request access to your contacts, microphone, or precise GPS location.

## 3. Optional app usage analytics
**Share app usage**, in **App Settings → Optional sharing**, controls Google Analytics for Firebase. It starts off on a fresh installation. Updates preserve your saved choice, and the tools work while it is off.

If you enable this choice, AngleMate sends fixed page names when you open its tools or settings. Google also processes automatic app and session activity, an app-instance identifier, device and app information such as operating-system and app versions, general geography derived from network addresses, and SDK operational diagnostics. We use this information to understand app usage and improve AngleMate.

The receiving service necessarily receives connection information, including your IP address. Google states that Analytics does not log or store IP addresses; it can derive general geography before discarding them. See [Google Analytics data safeguards](https://support.google.com/analytics/answer/6004245).

AngleMate disables advertising-ID collection and keeps advertising consent categories denied. Google signals, user-provided data collection, granular location/device data collection, and ads personalization are disabled in the production Analytics configuration. These restrictions do not remove all device or general-location information from Analytics. Measurements, calibration values, and camera images are not sent.

See [Privacy and Security in Firebase](https://firebase.google.com/support/privacy) and [Google's Privacy Policy](https://policies.google.com/privacy). Google Analytics is a separate service with its own terms, even when used through Firebase.

## 4. Optional error reporting
**Share error reports**, in **App Settings → Optional sharing**, controls Sentry reporting independently of app usage sharing. It starts off on a fresh installation. Updates preserve your saved choice, and the tools work while it is off.

If you enable this choice, AngleMate sends technical reports about managed .NET application errors to Sentry. Reports can include exception types, function and module names, stack frames, technical symbol identifiers, app version, and reporting environment. We use these reports to diagnose and fix errors.

The managed reporter removes arbitrary exception messages, user and request details, breadcrumbs, extra data, source directory paths, source snippets, and local-variable values. It does not attach camera images or measurement readings. The production Sentry project is configured to prevent stored IP addresses and scrub geography. Sentry still receives the network connection information needed to receive a report.

This release does not capture native crashes, session replays, logs, performance traces, or profiles. Fatal managed error delivery is best effort: a report may not arrive if the process terminates before sending finishes. Managed reports are not intentionally persisted to disk by AngleMate's reporter.

See [Sentry's Privacy Policy](https://sentry.io/privacy/).

## 5. Changing your sharing choices
You can change either sharing choice at any time in **App Settings → Optional sharing**. Keeping both off does not limit the measurement tools.

Turning usage sharing off disables collection and requests a reset of local Analytics data and its app-instance identifier. Turning error sharing off stops new app-managed reports and cancels pending managed sends. Information already received by a provider is not deleted by these switches. A request already sent cannot be recalled by turning sharing off.

For requests about provider-held data, see sections 9 and 10.

## 6. Advertising and payments
This release does not request advertising banners, start advertising consent collection, or process purchases. The Ad Free preview does not charge you or create a paid entitlement. We will review this policy and the store disclosures before introducing advertising or payments in a future release.

## 7. Information you provide when contacting us
If you contact **sb@iambell.com**, we receive your email address, message, and any information or attachments you choose to provide. We use them to respond, provide support, and handle privacy requests. Avoid sending sensitive information unless it is needed for your request.

## 8. Service providers and international processing
When you enable the corresponding sharing choice, Google processes usage information through Firebase Analytics, and Sentry processes error reports. Support communications are handled through the email services used to receive and answer them. We do not send measurement readings or camera previews to these providers.

We do not sell your personal information or use optional telemetry for cross-app advertising or ad personalization. Information may be disclosed when necessary to comply with applicable law or protect legal rights.

Google, Sentry, and their service providers may process information in countries other than your country of residence. The production Sentry organization uses its **United States** event-data region. Google Analytics processing is not restricted to a Firebase database or storage region. Google's information explains its [international data transfers](https://business.safety.google/adsdatatransfers/) and [Firebase processing locations](https://firebase.google.com/support/privacy).

## 9. Retention and deletion
Live measurements and camera previews are used during operation and are not saved as a measurement history or recording. Local preferences remain until changed, app storage is cleared, or the app is removed. Backups or device transfers may retain or restore settings separately.

On Android, you can remove local app data through **Settings → Apps → AngleMate → Storage → Clear storage**, or equivalent device controls. On iOS, deleting the app removes its app container; offloading retains its documents and data. Removing local data does not delete information already received by Google, Sentry, or an email service.

The production Analytics property is configured for **2 months** of user/event data retention, with reset on new activity off. This setting does not apply to standard aggregated reports. There are no configured Google Ads or BigQuery links in the reviewed production property. See [Google Analytics data retention](https://support.google.com/analytics/answer/7667196).

Our Sentry organization currently uses a free Business trial, followed by an automatic transition to the free Developer plan. Error events received during the trial retain their **90-day** retention period after the transition. New error events received after the transition have **30-day** retention. Switching plans does not shorten the retention of earlier trial events. These periods were confirmed by Sentry Support for our organization. See [Sentry's trial-expiry explanation](https://www.sentry.help/en/articles/13965075-what-happens-when-my-trial-expires).

We retain support communications for as long as reasonably necessary to address the inquiry and meet applicable legal obligations. Contact us to request deletion of information you provided or to ask about optional Analytics/error-reporting data.

Where an Analytics installation can be identified, Google offers user-data deletion. This does not remove standard aggregated reports, and provider processing is not immediate. Sentry groups events into issues; deleting an issue can affect several reports, so we must check its scope before acting. Neither operation establishes immediate erasure from every provider backup. Information independently controlled by a provider is also subject to that provider's privacy controls and policies.

## 10. Your privacy rights and identification limits
Depending on your location and applicable law, you may have rights to access, correct, delete, or obtain a copy of personal information, object to or restrict processing, withdraw consent, or complain to a data protection authority. Contact **[sb@iambell.com](mailto:sb@iambell.com)** about information we hold. We may need enough information to verify and respond to your request.

We cannot retrieve measurement readings or camera previews that the app never sends to us. Analytics and error reports do not contain an AngleMate account name or your email address, so an email address alone does not identify those records. The app does not currently offer an installation-ID or event-ID export feature. Resetting Analytics data can remove the identifier needed to associate earlier records with your installation.

We will assess whether we can locate the relevant records and explain any identification limits. We do not assume that a report belongs to you solely because its time, app version, or location appears to match. Turning sharing off does not itself delete provider-held data.

## 11. Security
AngleMate uses operating-system app storage and permission controls for local information. Optional Analytics uses encrypted transport, and the app accepts only HTTPS Sentry endpoints. No storage or transmission method can guarantee absolute security.

## 12. Children's privacy
AngleMate is a general-purpose measurement utility and is not directed to children under 13. If you believe a child has provided personal information to us, contact **[sb@iambell.com](mailto:sb@iambell.com)** so we can investigate and address the request.

## 13. Changes and contact
We may update this policy as AngleMate's features or data practices change. The latest version will be posted on this page with an updated date. We will provide any additional notice or request consent where applicable requirements call for it.

For questions or privacy requests, contact **Slava Bell** at **[sb@iambell.com](mailto:sb@iambell.com)**.
