# Day Chats — Privacy Policy

**Effective date:** 11 September 2026
**Developer:** Oscar Abrego (individual developer, "we", "us")
**Applies to:** the Day Chats iOS application ("the App"), including beta versions distributed through TestFlight

## 1. Summary

Day Chats is a personal diary that stores everything on your device. The App has no user accounts, no servers, and no analytics. We do not collect, receive, transmit, sell, or share any personal information. Your entries leave your device only when you export them yourself, or when you choose to send them to an AI provider you configured with your own key (section 7).

## 2. Information we collect

We collect **no** personal information. The App makes **no** network connections on its own; the only connections it ever makes are the ones described in section 7, which happen only if you register an AI provider key and only when you ask a question or analyze a calendar. Specifically, the App does not collect or transmit to us:

- your diary entries, photos, or captions;
- your name or reference name;
- device identifiers, location, contacts, or usage analytics;
- crash reports (see section 8 for TestFlight).

## 3. Information stored on your device

The App stores the following data locally, in the App's private container on your device:

- **Diary entries**: the text you write, the day each entry belongs to, and the time it was written.
- **Photos you add**: a copy of each photo you choose, kept inside the App. Adding a photo does not give the App access to your photo library.
- **Photo descriptions**: short machine-generated tags for photos you add, produced on your device by Apple's Vision framework. They are used only in your exports and are never sent anywhere.
- **Preferences**: the name you chose to be referenced by, the selected theme, and the Face ID and lock-delay settings.
- **AI answers and calendars** (only if you use the optional AI features, section 7): the answers to questions you asked, and the calendars you set up, meaning the question, its answer categories, and each day's answer with a short reason. They stay on your device and are included in backups you make.

This data is protected with iOS data protection while your device is locked. It is included in your device's iCloud or computer backups, which are governed by Apple's privacy policy, not by ours.

## 4. Face ID

If you enable the Face ID lock, authentication is performed entirely by iOS. The App only learns whether the check succeeded. It never accesses, stores, or transmits biometric data.

## 5. Device permissions

- **Camera**: used only when you choose to take a photo for an entry.
- **Photo library (add only)**: used only to save a photo you took from within the App back to your library, if you allow it. The App cannot read your library through this permission.
- **Photo picker**: when you choose an existing photo, iOS presents its own picker and shares only the photos you select.

You can change these permissions at any time in the iOS Settings app.

## 6. Exports and sharing

The App can render your entries as a text file or copy them to the clipboard. This happens only when you tap an export or copy action. What you do with an exported file, including sharing it with other apps or services, is under your control and subject to those services' policies.

## 7. Optional AI features and third-party providers

The App can answer questions about your diary, and sort your days onto a calendar by a question you choose, using an AI provider such as OpenAI. This is off until you register your own API key for that provider in Settings.

- **What is sent:** when you ask a question, the App sends the provider your question and the diary entries in the date range you selected (text, photo captions, and the on-device photo tags). When you analyze a calendar, it sends that calendar's question and the entries of the days being analyzed, in small batches; later updates send only days that are new or changed. When you type a question to set up a calendar, only that sentence is sent, so the provider can suggest answer categories. Photos themselves are never sent. Nothing is sent at any other time.
- **Who receives it:** only the provider you chose, under that provider's own terms and privacy policy, using your key and your account with them. We are not a party to that transfer and receive nothing.
- **Your key:** stored in the iOS Keychain on your device only. It is never included in exports or backups, and it is not sent anywhere except to that provider to authenticate your requests.
- **Answers and calendars:** stored on your device with your entries; you can delete them at any time.

Apart from this, the App uses no third-party software development kits, advertising, analytics, or cloud services. We share no information with anyone.

## 8. TestFlight beta versions

If you use a beta version through Apple's TestFlight, Apple may collect crash logs, usage statistics, and any feedback or screenshots you choose to submit, under Apple's TestFlight terms and privacy policy. We receive only what Apple provides to developers through TestFlight, such as crash reports and feedback you submit, and we use it solely to fix problems in the App.

## 9. Data retention and deletion

Your data stays on your device for as long as you keep it. You can delete individual entries, photos, or whole days inside the App. Deleting the App removes all of its data from your device. Copies in your device backups are managed by iOS and Apple.

## 10. Children

The App is not directed to children under 13, and we do not knowingly collect information from anyone, including children.

## 11. Security

Data is stored in the App's private container with iOS file protection enabled. Because the App never transmits data, there is no data in transit to secure. No method of storage is completely secure, and we recommend keeping your device passcode and backups protected.

## 12. Changes to this policy

If we change this policy, we will update the effective date above and publish the new version at the same address. Continued use of the App after a change means you accept the updated policy.

## 13. Contact

Questions about this policy or the App: support@daychats.com
