# BananaBucks Privacy Policy

**Effective date: October 9, 2026**

This is the privacy policy for **BananaBucks** (bundle ID `dev.dcreey.Spend`, iOS), published by Dylan Yurgionas (GitHub: [dcreey](https://github.com/dcreey)). It's short because there isn't much to say: the app doesn't collect anything.

## The short version

- **No data is collected.** Not analytics, not crash reports, not device identifiers, not usage statistics. Nothing.
- **There is no backend.** The app doesn't talk to any server operated by the developer. There is no account system, no sign-in, and nothing to sync. The only network request is a public download of currency exchange rates (see [Network requests](#network-requests-to-public-services)).
- **Everything stays on your device.** The expenses you enter are stored only on your iPhone and are never transmitted anywhere.
- **No tracking.** No advertising SDKs, no analytics SDKs, no third-party trackers of any kind are included in the app.
- **No third-party sharing.** Since nothing is collected, there is nothing to share, sell, or disclose to anyone, including the developer.

## Permissions

BananaBucks doesn't ask for any permissions: no camera, photos, location, contacts, or notifications.

## Data stored on your device

The app stores the following **only on your device**. None of it is sent to the developer or anyone else:

- **Expenses and trips:** the expenses you enter (amount, currency, category, note, date, and an optional trip), including how an expense is spread across months, kept in the app's own storage. Deleting the app deletes them. You can also delete expenses inside the app.
- **Settings:** your language choice and recently used currencies.
- **Cached exchange rates:** the latest currency exchange rates, kept on your device so expenses can be converted to US dollars offline.

## Network requests to public services

The app doesn't send your expenses, notes, or anything else you enter anywhere. One narrow request exists:

- **Exchange rates:** to convert expenses to US dollars, the app downloads a public table of currency exchange rates from `open.er-api.com`. The request is a plain download of that table and contains none of your data. Like any web request, the server can see your device's IP address, and that service's own privacy practices apply. If the request fails, the app uses the last saved rates or built-in estimates.

## Children's privacy

Since no data is collected from anyone, no data is collected from children either.

## Changes to this policy

If this policy changes, the date at the top of this page will change, and a summary of what changed will be noted in this repository's commit history, which is public.

## Contact

Questions about this policy: **dcreey@gmail.com**. For app support (bugs, questions, feature requests), see [SUPPORT.md](SUPPORT.md).

## Back to all policies

[All apps](README.md) · [Support](SUPPORT.md)
