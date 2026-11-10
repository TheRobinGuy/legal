---
title: Line of Fire privacy policy
permalink: /line-of-fire/privacy/
---

# Line of Fire privacy policy

Last updated: 10 November 2026

Line of Fire is a stickman shooter made by Seanchas, in Ireland. This policy says what the app does with your information.

**In short: your progress stays on your phone. There is no account, no advertising and no tracking across other apps.**

## What stays on your phone

Your save (stages cleared, scores, coins, unlocks, settings) is stored in the app's own storage. We never receive it.

**Android backup.** If backup is on for your phone, Android may copy your save to your Google account so it can be restored on a new phone. Google handles that under its own terms; we can't see it. You can turn it off in your phone's settings.

## Crash reports

<!-- Matches the build: opt-in, asked once after the first crash, Settings > Privacy switch. CHECK before release: the retention below equals the Sentry project's setting, and "Prevent Storing of IP Addresses" is on. -->
Crash reports are off until you say yes. The first time the game crashes it asks once whether to send crash reports; you can change your answer any time in Settings, under Privacy. If you say yes, reports go to Sentry (Functional Software, Inc.), which acts as our processor. If you are offline, reports wait on your phone and are sent next time you are online and playing. Switching reports off deletes any that are still waiting.

A report holds: the error message and stack, the app version, the stage, mode and difficulty you were playing, whether you own the Full Game (so we can tell if paying players hit a problem), your phone model and Android version, and a random install ID the app makes. It holds no name, email, Google account, device ID or save contents, and we ask Sentry not to store IP addresses. Sentry keeps reports for 90 days.

## Purchases

<!-- Matches the build: one non-consumable "Full Game" via Google Play, with RevenueCat checking ownership. Update if the product list changes. -->
The free part of the game is World 1, the Daily run and the Locker. A one-time purchase, the Full Game, unlocks the rest. Payment is handled entirely by Google Play. We never see your card or payment details.

To know what you own, the app uses RevenueCat, Inc., which acts as our processor. The app gives RevenueCat a random app user ID it makes, and RevenueCat checks your purchase with Google Play and tells the app whether the Full Game is owned. RevenueCat holds that ID, your purchase and its status, and, as any service on the internet does, receives your IP address when the app connects. The app remembers the answer on your phone so the game works offline. To restore your purchase on a new phone, use "Restore purchase" on the Full Game screen.

## Access codes

If you type an access code (for example, one given to a Google Play app reviewer), the app sends the code and your random app user ID to a function we run on Supabase, Inc., our processor. It checks the code and, if it is right, asks RevenueCat to switch the Full Game on for that ID for 30 days. The function's logs may keep the ID and the result for a short time. Nothing is sent unless you press Unlock.

## Permissions

The app uses the internet to check what you own, to send crash reports if you allowed them, and to check an access code if you enter one. It does not use your location, contacts, camera or microphone.

## Children

The app is a cartoon-violence action game and is not aimed at children under 13. We do not knowingly collect information from children.

## Your choices and contact

You can switch crash reports on or off in Settings, turn off Android backup, or uninstall the app, which removes the save from your phone. To ask about data, contact: seanchas.apps@gmail.com

## Changes

When the app starts sending data somewhere new, this policy changes in the same release, with a new date above. The history is in this site's git repository.
