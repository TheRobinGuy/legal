---
title: Wild Swim Log privacy policy
permalink: /wild-swim-log/privacy/
---

# Wild Swim Log privacy policy

> **Draft, not yet in effect.** TODO before publishing: fill the developer's legal name and the contact address, set
> the date below, remove this notice, and have the policy reviewed (not legal advice). Re-check it against the
> release build and the Play Data safety form.

Last updated: TODO

Wild Swim Log is a swim logbook made by Seanchas (TODO: legal name as registered in the Play Console). This policy
says what the app does with your information.

**In short: your swims, notes and photos stay on your phone unless you turn on Cloud sync. Photos never leave your
phone at all. There is no advertising and no tracking across other apps.** There is no account unless you choose to
link an email address to a Cloud sync backup.

## What stays on your phone

Your swim logs (title, date, place, coordinates if you added them, duration, notes, tags, water temperature and the
other fields you log), your photos and voice notes, and your settings are stored on your phone, in the app's own
storage. **Photos and voice notes are never uploaded anywhere**, even with Cloud sync on: sync sends only a count of
how many a swim has.

If you never buy Cloud sync, none of your swim data leaves your phone except as described under "Lookups the app
makes" and "Copies you choose to make" below.

## Cloud sync (a paid add-on)

If you buy Cloud sync and turn it on, the app copies your swim logs to our database, hosted by Supabase, so they
survive losing your phone and can be restored on a new one. What is copied: everything in a swim log except photos
and voice notes. It is tied to a random identity the app creates the first time it syncs; that identity has no name
or email.

**Account recovery (optional).** To restore your swims after a reinstall or on a new phone, you can link an email
address under Settings → Cloud sync. We use it only to email you a one-time sign-in code. We never ask for a
password, and we never use the address for marketing. If you don't link one, we have no way to tell which backup is
yours.

Deleting a swim in the app marks it deleted in the cloud copy and removes it from your other devices on their next
sync. TODO: update this paragraph when the account-deletion work lands (the deleted copy is currently kept, in full,
until the account is deleted). To remove everything we hold, see "Deleting your data".

## Lookups the app makes

Some features fetch public information. These requests go from your phone straight to the services below. They carry
your IP address, as any web request does, and the details given here; none of them receives your name, your email or
any identifier from us.

| Feature | What is sent | To whom |
| --- | --- | --- |
| Maps (a swim's map, the logbook map, Water quality, the pin picker) | Which part of the map is on screen, and the zoom. That is often somewhere you have swum or plan to. | OpenFreeMap (tiles.openfreemap.org) |
| Search for a place, or typing in a swim's Where field | The text you type, once it is three or more characters, with a fixed area covering western Europe (not your position) | Photon, run by komoot GmbH (photon.komoot.io), on OpenStreetMap data |
| My location in the swim editor, with Where empty and not at a spot you have logged | Your coordinates rounded to about 10 m, to name the spot | Photon, as above |
| Water quality, weather and "check before you swim" (paid Conditions data add-on) | The coordinates of the place you are viewing | Public data services: the Environment Agency, Natural Resources Wales, Ireland's EPA, DAERA (Northern Ireland), MET Norway, and the public storm-overflow feeds of English and Scottish water companies |

Tide times and most bathing-water classifications are bundled with the app and worked out on your phone, so looking
at them sends nothing.

**Location permission.** The app asks for your location only when you tap a button that needs it (such as My
location in the editor, or a nearby search). It does not read your location in the background. Approximate location
is enough. You can take the permission back in your phone's settings at any time.

## Crash reports and usage signals

When the app hits an error, it sends a crash report to Sentry (Functional Software, Inc.): your phone model, Android
version, app version, what went wrong and where in the code. It also sends anonymous usage signals, for example that
the app was opened, that a swim was added, or that a sync or purchase failed. They carry a random identifier (the
same one used for your purchases, below), not your name or email, and never the text of your swims. We use them to fix
bugs.

## Purchases

Payments are handled by Google Play; we never see your card or payment details. The app uses RevenueCat (RevenueCat,
Inc.) to check what you have bought, so your add-ons unlock and can be restored on a new phone. RevenueCat receives a
random app user ID, your purchase records and basic device details.

## Copies you choose to make

Data only leaves the app when you, or Android at your request, copy it:

- **Export and backup files.** Exporting your swims (CSV or JSON) makes a file; you choose where it goes.
- **Share a swim.** The app makes a picture of a swim and hands it to the app you choose.
- **Android backup.** If backup is on for your phone, Android may copy the app's data to your Google account, under
  Google's terms. You can turn it off in your phone's settings.

## What we don't do

- No advertising, and no advertising identifiers. (TODO: confirm after the `play-services-ads-identifier` check.)
- No selling or sharing of your information.
- No tracking across other apps or websites.

## Who handles your data for us

| Service | What it handles | Its policy |
| --- | --- | --- |
| Supabase (Supabase Inc.) | Cloud sync copy of your swims, the random sync identity, and the recovery email if you link one | [supabase.com/privacy](https://supabase.com/privacy) |
| Sentry (Functional Software, Inc.) | Crash reports and usage signals | [sentry.io/privacy](https://sentry.io/privacy/) |
| RevenueCat, Inc. | Purchase status and a random app user ID | [revenuecat.com/privacy](https://www.revenuecat.com/privacy/) |
| Google Play | Payments and app delivery | [policies.google.com/privacy](https://policies.google.com/privacy) |

Each acts on our instructions as a processor, under its own data processing terms. TODO: record where each stores
data (regions) once the projects are fixed, and how long Sentry keeps reports.

## Deleting your data

- **On your phone:** deleting a swim removes it from the app. Uninstalling the app removes everything it stored on
  your phone.
- **In the cloud:** in the app, go to Settings → Cloud sync → Delete my cloud data. This deletes every swim we hold for
  your sync identity and the identity itself, including a linked email. TODO: this button is being built; remove this
  notice when it ships.
- **Without the app** (you have lost your phone, or uninstalled): use the request page at
  [Delete your Wild Swim Log data](../delete-account/). If you linked an email, we can find and delete your backup
  from it. If you never linked one, we cannot tell which backup is yours, so there is nothing we can look up; that
  backup holds only your swims, under an identity with no name.
- **Purchases:** Google Play and RevenueCat keep purchase records as the law requires. Deleting your cloud data does
  not cancel a subscription; manage subscriptions in Google Play.

## Children

Wild Swim Log is not directed at children, and we do not knowingly collect information from anyone under 16. Swimming
outdoors can be dangerous, especially for children and in cold water: the app's safety notes are information, not
advice.

## Your rights

If you are in the EU, the EEA or the UK you can ask us for a copy of your information, to correct or delete it, or to
restrict or object to how we use it. Write to us at the address below. You can also complain to your data protection
authority; in Ireland that is the Data Protection Commission (dataprotection.ie).

## Changes

If this policy changes, the new version is posted here with a new date. Every past version is kept in
[this page's history](https://github.com/TheRobinGuy/legal/commits/main/wild-swim-log/privacy.md).

<!-- WHEN Health Connect import ships (backlog, not in v1), add a section here: what is read (open-water swim
     sessions: start, end, title, and distance), that it is read only after the user allows it, kept on the phone
     as ordinary swims, never written back, and never sent anywhere except through Cloud sync if the user has it on.
     Also file Play's health-permissions declaration and update the Data safety form first (review has lead time). -->

<!-- WHEN EEA or Italian bathing-water data ships, name the EEA as the source of the bundled classifications and
     update the date. The data is bundled, so no new request is made. -->

<!-- WHEN a new network service, SDK or permission is added, add a row or section here in the same release, and
     update the Data safety form. -->

## Contact us

TODO: contact email address
