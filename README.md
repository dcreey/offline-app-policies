# Offline App Privacy Policy

**Effective date: September 27, 2026**

This is the privacy policy for apps published by Dylan Yurgionas (GitHub: [dcreey](https://github.com/dcreey)) that are covered by it — see [Apps covered by this policy](#apps-covered-by-this-policy) below. It's short because there isn't much to say: these apps don't collect anything.

## The short version

- **No data is collected.** Not analytics, not crash reports, not device identifiers, not usage statistics. Nothing.
- **There is no backend.** These apps don't talk to any server operated by the developer. There is no account system, no sign-in, and nothing to sync.
- **Everything runs on your device.** Any processing the app does — reading text from a photo, matching it against a bundled database, showing a result — happens entirely on-device, offline, using on-device frameworks (e.g. Apple's Vision and Foundation Models APIs). Nothing you photograph, type, or select is ever transmitted anywhere.
- **No tracking.** No advertising SDKs, no analytics SDKs, no third-party trackers of any kind are included in these apps.
- **No third-party sharing.** Since nothing is collected, there is nothing to share, sell, or disclose to anyone, including the developer.

## What permissions these apps ask for, and why

An app covered by this policy may ask for permission to use your **camera** or **photo library**. That access is used only so you can point the app at something or pick a photo to process — the resulting image is handled entirely on your device for that single operation and is not saved, uploaded, logged, or transmitted anywhere by the app.

## Outbound links

Some apps link out to third-party websites (for example, a rating or review site for something the app identified). Tapping one of those links opens that third party's site in your browser, and their own privacy policy applies to whatever happens there. The app itself does not send them anything about you beyond your device making a normal request to load their page, the same as if you'd typed the URL in yourself.

## Children's privacy

Since no data is collected from anyone, no data is collected from children either.

## Changes to this policy

If this policy changes, the date at the top of this page will change, and a summary of what changed will be noted in this repository's commit history, which is public.

## Contact

Questions about this policy or any app it covers: **dcreey@gmail.com**

## Apps covered by this policy

| App | Bundle ID | Platform |
|---|---|---|
| [Bottle ID](https://github.com/dcreey/bottle-id) | `dev.dcreey.BottleID` | iOS |

To add another app to this policy, add a row to the table above in a pull request or commit — the policy text itself doesn't need to change unless that app actually does something different (in which case it shouldn't be listed here).
