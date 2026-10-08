# Offline App Privacy Policy

**Effective date: October 8, 2026**

This is the privacy policy for apps published by Dylan Yurgionas (GitHub: [dcreey](https://github.com/dcreey)) that are covered by it — see [Apps covered by this policy](#apps-covered-by-this-policy) below. It's short because there isn't much to say: these apps don't collect anything.

## The short version

- **No data is collected.** Not analytics, not crash reports, not device identifiers, not usage statistics. Nothing.
- **There is no backend.** These apps don't talk to any server operated by the developer. There is no account system, no sign-in, and nothing to sync. A few apps do make narrow requests to public third-party services (see [Network requests](#network-requests-to-public-services)).
- **Everything runs on your device.** Any processing the app does — reading text from a photo, matching it against a bundled database, showing a result — happens entirely on-device, offline, using on-device frameworks (e.g. Apple's Vision and Foundation Models APIs). Photos you take or pick, and text you type, are never transmitted anywhere.
- **No tracking.** No advertising SDKs, no analytics SDKs, no third-party trackers of any kind are included in these apps.
- **No third-party sharing.** Since nothing is collected, there is nothing to share, sell, or disclose to anyone, including the developer.

## What permissions these apps ask for, and why

An app covered by this policy may ask for permission to use your **camera** or **photo library**. That access is used only so you can point the app at something or pick a photo to process — the image is processed entirely on your device and is never uploaded, logged, or transmitted anywhere. Some apps keep a history on your device (see [Data stored on your device](#data-stored-on-your-device)); you can delete it inside the app, or by deleting the app.

## Data stored on your device

Apps covered by this policy may store the following **only on your device**. None of it is sent to the developer or anyone else:

- **Scan history** (Bottle ID / Best in Glass): the photos you scanned, which bottles were identified, and the bottles you looked up, kept in the app's own storage so you can revisit them. Deleting the app deletes them.
- **Cached label images**: pictures of product labels downloaded for display, kept in the app's cache.
- **Free-scan counter** (Best in Glass): a short list of one-way hashes (fingerprints) of up to 5 photos you've scanned, kept in the iOS Keychain so a photo can be rescanned for free and the free allowance survives a reinstall. A hash cannot be turned back into the photo. The Keychain entry stays on your device; Apple may sync Keychain data you have enabled in iCloud Keychain, which is Apple's service, not ours.

## Network requests to public services

The apps don't send your photos or searches anywhere. These narrow requests exist:

- **Label images (Best in Glass / Bottle ID):** to show a sharp copy of a product's label, the app downloads it from the U.S. Treasury TTB Public COLA Registry (`ttbonline.gov`). The request names only the public label-approval ID of the bottle being shown, never your photo. Like any web request, the TTB server can see your device's IP address; the U.S. government's own privacy practices apply.
- **In-app purchase (Best in Glass):** unlocking scanning is a one-time purchase handled entirely by Apple (StoreKit). Apple processes the payment and gives the app a signed receipt that is checked on your device. The developer receives no payment details, account name or email.

## Outbound links

Some apps link out to third-party websites (for example, a rating or review site, or a competition's results page, for something the app identified). Tapping one of those links opens that third party's site in your browser, and their own privacy policy applies to whatever happens there. The app itself does not send them anything about you beyond your device making a normal request to load their page, the same as if you'd typed the URL in yourself.

## Children's privacy

Since no data is collected from anyone, no data is collected from children either.

## Changes to this policy

If this policy changes, the date at the top of this page will change, and a summary of what changed will be noted in this repository's commit history, which is public.

## Contact

Questions about this policy or any app it covers: **dcreey@gmail.com**. For app support (bugs, questions, feature requests), see [SUPPORT.md](SUPPORT.md).

## Apps covered by this policy

| App | Bundle ID | Platform |
|---|---|---|
| [Best in Glass](https://github.com/dcreey/bottle-id) (formerly Bottle ID) | `dev.dcreey.BottleID` | iOS |

To add another app to this policy, add a row to the table above in a pull request or commit — the policy text itself doesn't need to change unless that app actually does something different (in which case it shouldn't be listed here).
