---
title: Rollmint Privacy Policy
permalink: /rollmint/privacy
---
# Rollmint Privacy Policy

_Effective date: October 25, 2026 · Last updated: October 25, 2026_

Rollmint is an iPhone app by Joshua Manson ("we", "us") that helps you review, pick, search and delete photos and videos in your photo library. This policy explains what happens to your information when you use it.

## Summary
- **Rollmint never uploads your photos.** It reads, analyzes and deletes them only on your iPhone. Your photos and videos are not sent to us or to anyone else.
- **Photo analysis and search happen on your iPhone.** Rollmint uses Apple's on-device Vision framework to recognize what's in your photos (for example "dog", "receipt" or "beach") so you can search them. The results stay on your device.
- **The only data collected is purchase history,** which RevenueCat processes so your purchase can be unlocked and restored. It is not linked to your identity and not used for tracking.
- **No accounts, no ads, no tracking, and no analytics SDKs.** We run no servers that receive your data.

## Photos and videos
Rollmint asks for access to your photo library so it can show you your photos and videos and delete the ones you choose. All of this happens on your device: browsing, grouping by year and month, showing month collages, filtering screenshots, analyzing and searching photos, and estimating storage. To make the collages and run the analysis, Rollmint uses small thumbnails from your device. It does not download originals from iCloud for this, and it uses no network connection.

Deletions go through Apple's photo library framework, and iOS asks you to confirm each one. Deleted items move to the "Recently Deleted" album, where iOS keeps them for up to 30 days. Your keep, delete and pick choices and your deletion counts are stored only on your device.

You can give Rollmint full or limited photo access, and change it at any time in Settings › Privacy & Security › Photos › Rollmint.

## On-device photo analysis and search
To let you search your library by what's in a photo (for example "dog" or "beach"), Rollmint uses Apple's Vision framework to analyze small thumbnails of your most recent photos (up to 5,000), entirely on your iPhone. Videos aren't analyzed. Analysis never uses the network: a photo stored only in iCloud, with no copy on your iPhone, is skipped rather than downloaded.

The analysis keeps a small **index** on your device. For each photo, it holds:
- the photo's library identifier and its creation and modification dates
- the labels Apple's framework detected, with a confidence score
- a few technical image measurements used by the analysis: a compact visual fingerprint (a "feature print") and simple quality scores

The index lives only in Rollmint's private storage on your device. It is never sent anywhere and is never shared. When a photo is deleted from your library, its entry is removed from the index.

Searching works the same way. What you type is matched against the index on your device. Your search queries are never sent anywhere and aren't stored beyond the search itself. The search filters (date, Screenshots, Live Photos, With location) read those details from your photo library on your device at the moment you search. Rollmint does not store your photos' locations, does not look up place names, and never asks for location access.

**You're in control:** turn analysis off at any time with the "Analyze photos on this iPhone" switch in Rollmint › Settings › Photo Search. Turning it off stops the analysis and deletes the whole index from your device, including its labels, feature prints and scores.

## Month Picks and recap cards
If you mark photos as picks, Rollmint can add them to an album named "Best of [Month Year]" in your own photo library. Un-picking a photo removes it from that album, and the photo stays in your library.

Rollmint can also make a recap image (a 3×3 grid of your picks with simple stats). The recap is created on your device. It is saved to your library only if you tap Save, and it is shared only if you choose to share it through the iOS share sheet. Rollmint never sends it anywhere.

## Notifications
If you turn on the Month Picks reminder, Rollmint schedules a **local** notification on your iPhone for the last day of each month. Rollmint uses no push service and no device token, and no notification data leaves your device. You can turn the reminder off in Rollmint › Settings, or in iOS Settings › Notifications › Rollmint.

## iCloud Photos
If you use iCloud Photos, Apple keeps your library in sync across your devices. That happens between your devices and Apple, and Rollmint doesn't receive a copy. Deleting an item in Rollmint deletes it from your library on every device that uses iCloud Photos, and it stays in Recently Deleted for 30 days. When you play a video that is stored only in iCloud, iOS may download it from Apple to play it. Rollmint itself never uploads your photos.

## Purchases (RevenueCat and Apple)
Rollmint offers a one-time "Rollmint Pro" purchase.
- **Apple** handles all payments through the App Store. We never see or receive your payment details. Apple's privacy policy applies: <https://www.apple.com/legal/privacy/>.
- **RevenueCat, Inc.** is the service we use to check and restore purchases. When Rollmint checks your Pro status, or when you buy or restore, RevenueCat processes **purchase history**: the App Store transaction and receipt details, together with a random anonymous app user ID that RevenueCat generates.
  - It is used to provide app functionality (unlocking Pro and restoring it) and for aggregate purchase statistics in RevenueCat's dashboard (for example, how many people bought Pro).
  - It is **not linked to your identity** and is **not used for tracking** or advertising.
  - RevenueCat's privacy policy applies: <https://www.revenuecat.com/privacy>.

## Third parties
RevenueCat, Inc. processes purchase information only to validate and restore purchases and to provide aggregate purchase statistics. Apple processes payments under its own privacy policy. We share data only with service providers that provide the same or equal protection of user data as stated in this policy.

## Tracking, advertising and analytics
Rollmint does not track you across apps or websites and shows no ads. It contains no advertising SDKs, no analytics SDKs and no crash-reporting SDKs. The only statistics are RevenueCat's aggregate purchase statistics described above.

## Data retention and deletion
- **On your device:**
  - Your choices, picks, stats and the search index stay on your device until you delete them.
  - Use Settings › Reset review progress to clear choices and picks. Turn off Photo Search to delete the index.
  - Deleting the app removes all of its on-device data. One exception: the free-deletion counter is kept in the device Keychain so it survives a reinstall, and it holds no personal information.
- **"Best of" albums and saved recaps** are in your own photo library. You can delete them there.
- **Purchase history at RevenueCat** is kept as long as needed to restore your purchase and for RevenueCat's records, under RevenueCat's privacy policy. Because it isn't linked to your identity, we can't look it up by name or email. To ask for access to it or deletion of it, email us with your App Store receipt or order ID from <https://reportaproblem.apple.com>, and we'll work with RevenueCat on your request.
- **Emails you send us** are kept only as long as needed to answer you. Ask us to delete them at any time.

## Your rights
Depending on where you live, you may have rights to access or delete your personal data. Because Rollmint keeps your data on your device, you can exercise most of them yourself by turning features off, using Reset review progress, or deleting the app. For purchase data held by RevenueCat, email us as described under "Data retention and deletion".

## Children
Rollmint is not directed at children and does not knowingly collect personal information from anyone.

## Changes
If this policy changes, the updated version will be posted on this page with a new "Last updated" date.

## Contact
Rollmint is published by Joshua Manson, the developer of Rollmint. Email **[RollmintSupport@icloud.com](mailto:RollmintSupport@icloud.com)** or see the [Support page](support).
