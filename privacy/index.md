---
layout: default
title: "Privacy Policy"
effective_date: "August 25, 2026"
---

MyBibleSpark ("we," "our," or "the app") is a daily Bible companion for iOS and Android.
We are committed to protecting your privacy. This policy explains what information is
collected, how it is used, and your rights.

## Information We Collect

| Data | Where stored | Purpose |
|------|-------------|---------|
| Name and/or email address (from Sign in with Apple or Google) | <span class="badge badge-remote">Sent to server</span> | Creates and secures your account; see "Account and Sign-In" below |
| Your mood and spiritual goal selections | <span class="badge badge-remote">Sent to server</span> | Passed to our AI service to personalize your daily passage |
| Preferred Bible translation (KJV) | <span class="badge badge-remote">Sent to server</span> | Determines which translation is returned for your passage |
| Recently viewed Bible references (last 7) | <span class="badge badge-remote">Sent to server</span> | Helps avoid repeating passages you have seen recently |
| Daily passage request count, linked to your account | <span class="badge badge-remote">Sent to server</span> | Enforces the daily usage limit for your subscription tier |
| Device identifier (iOS `identifierForVendor` / Android `ANDROID_ID`) | <span class="badge badge-remote">Sent to server</span> | Prevents free-tier quota abuse by switching accounts on the same device; not linked to your account identity |
| Cached daily passage and reading history | <span class="badge badge-local">On-device only</span> | Lets you revisit previous passages without an internet connection |
| Notification preference and reminder time | <span class="badge badge-local">On-device only</span> | Schedules your local daily reminder |
| Onboarding completion flag | <span class="badge badge-local">On-device only</span> | Skips the intro flow on subsequent launches |

We do not collect your location, and we never see or store your payment card details.
Your mood, goal, translation, and recent-reference selections are used only to generate
that day's passage request and are not retained on our servers beyond that request.

## Account and Sign-In

MyBibleSpark requires you to sign in with **Sign in with Apple** or **Sign in with
Google** before you can use the app — this is what keeps your subscription and daily
usage tied to you personally rather than to a specific device or install. Account
authentication is handled by **Firebase Authentication**, a service operated by Google.

Depending on which provider you use and the choices you make during sign-in:

- **Sign in with Apple** shares your name and either your real email address or an
  Apple-generated private relay address, depending on whether you choose to hide your
  email.
- **Sign in with Google** shares the name and email address associated with your Google
  account.

We use this solely to identify your account, secure it against being used by anyone
else, and enforce your subscription's daily passage limit. We do not use it for
marketing and do not share it with advertisers.

## How We Use Your Information

The mood, goal, translation, and recent-reference data listed above are sent to our
server solely to generate your personalized daily Bible passage. This request is
forwarded to **Anthropic, PBC** ("Claude AI"), a third-party artificial intelligence
provider. Anthropic may process this data according to its own
[Privacy Policy](https://www.anthropic.com/privacy).
We do not sell or rent your data, and we do not share it with any third party other
than the service providers described in this policy.

## Third-Party AI Service (Anthropic)

MyBibleSpark uses the Claude API, operated by Anthropic, PBC, to generate scripture
passages and reflections. When you request a passage, the following non-identifying
inputs are sent: your selected mood, spiritual goal, preferred translation, and a
short list of recent Bible references. No device identifiers or personal details are
included in this request.

Anthropic's data practices are governed by their
[Privacy Policy](https://www.anthropic.com/privacy).

## Authentication and Account Storage (Firebase)

We use **Firebase**, a service operated by Google, to authenticate your sign-in and to
store a minimal, account-linked record on our server: your account identifier and a
count of how many passages you have requested today. This count resets daily and is
automatically deleted within about 48 hours of being created.

We also store a separate, device-linked request count keyed to your device identifier
rather than your account, used only to prevent the free-tier daily limit from being
multiplied by switching accounts on the same device. This device-linked count is not
tied to your account identity, is not affected by account deletion, and is automatically
deleted within about 48 hours of being created.

Google's data practices are governed by their
[Privacy Policy](https://policies.google.com/privacy) and
[Firebase's privacy and security documentation](https://firebase.google.com/support/privacy).

## Subscription Management (RevenueCat)

We use **RevenueCat, Inc.** to manage subscription entitlements across the App Store and
Google Play. Your account identifier and subscription status are shared with RevenueCat
so the app can determine which features and daily limits apply to you. RevenueCat's data
practices are governed by their [Privacy Policy](https://www.revenuecat.com/privacy).

## In-App Purchases and Subscriptions

MyBibleSpark offers optional auto-renewing subscriptions for expanded access. All payment
transactions are processed entirely by **Apple (App Store)** or **Google (Google Play)**
— we never see or store your payment card details.

Apple's and Google's data practices are governed by their respective privacy policies.

## Push Notifications

If you enable daily reminders, the app schedules a **local notification** entirely on
your device. No notification content is sent from a remote server, and no device token
or notification identifier is transmitted to us or any third party. You can disable
notifications at any time in the app's Settings screen or in your device's system
notification settings.

## Data Retention and Deletion

On-device data (cached passages, reading history, and preferences) is stored in your
device's local storage. You can delete this data at any time by uninstalling the app.

Your account — your Firebase sign-in record, your daily usage count, and your
RevenueCat subscriber record — can be permanently deleted at any time from within the
app: go to **Settings → Delete Account**. This immediately and permanently deletes your
account and cannot be undone. You can also request deletion by contacting us at the
email address below.

Deleting your account does **not** cancel an active auto-renewing subscription — Apple
and Google, not us, control that billing relationship. To stop being charged, cancel
your subscription in your Apple App Store or Google Play account settings before or
after deleting your account.

## Children's Privacy

MyBibleSpark is not directed at children under 13 years of age. We do not knowingly
collect personal information from children. If you believe a child has provided
information through the app, please contact us so we can address it promptly.

## Changes to This Policy

We may update this privacy policy from time to time. When we do, we will revise the
effective date at the top of this page. Continued use of the app after changes are
posted constitutes your acceptance of the revised policy.

## Contact Us

If you have questions about this privacy policy or our data practices, please contact
us at [mybiblespark@gmail.com](mailto:mybiblespark@gmail.com).
