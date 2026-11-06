---
title: Privacy Policy
permalink: /privacy/
---

# Apollo for iPhone and Apple Watch: Privacy Policy

_Last updated: 6 November 2026_

Apollo is an app for Apollo, a self-hosted health data hub. You run the Apollo server yourself (on your own computer, NAS or server), and the app connects only to the server address you enter.

## What we collect

Nothing. The developers of Apollo do not operate any server that receives your data, and the app contains no analytics, advertising, tracking or crash-reporting SDKs. We never see, store, sell or share your data.

## Where your data goes

- **Your Apollo server.** Workouts, food, body metrics, sleep, water, supplements and anything you log in the app are sent to the Apollo server you sign in to, over the connection you configure (we recommend HTTPS). That server is operated by you, or by whoever gave you access to it, and its data is under their control.
- **Your device.** The app stores the server address and a sign-in token in the iOS/watchOS Keychain, and a few preferences (such as the last sync time) on the device.
- **Your Apple Watch.** The iPhone app sends the watch a separate token that can only read and log data, so the watch can reach your server. You can revoke it at any time in the Apollo web app (Settings → Tokens).

## Apple Health

If you turn on "Sync from Apple Health", the app reads the types you allow (such as weight, body fat, heart rate, heart rate variability, VO2 max, blood pressure, respiratory rate, blood oxygen, body temperature, steps, active and resting energy, distance, flights climbed, exercise minutes, water and sleep) and sends them to your Apollo server. On Apple Watch, the app can save the strength workouts you log, and reads heart rate and active energy during a workout to show them on screen.

Health data is never used for advertising or marketing, never sold, and never sent anywhere other than your own Apollo server. You can stop syncing at any time in the app's settings or in the Health app (Sharing → Apps).

## Camera

The camera is used only to scan food barcodes while the scanner is open. Images are processed on the device and are not stored or sent anywhere; only the barcode number is sent to your server to look up the food.

## Third-party food databases

When you search for foods, your server may query Open Food Facts or USDA FoodData Central on your behalf, depending on how it is configured. The app itself does not contact these services.

## Children

Apollo is not directed at children under 13.

## Deleting your account and data

In the app, go to Settings → Delete account and confirm with your password. Your Apollo server then permanently deletes the account and all of its data (measurements, food logs, workouts, photos, settings and tokens), and the app signs out on your iPhone and Apple Watch. You can do the same in the Apollo web app (Settings → Profile → Delete account). Data you keep in Apple Health stays there.

Signing out of the app (without deleting the account) removes the token and server address from the device and revokes the Apple Watch token.

## Contact

Questions about this policy: email [pirvanescudimitrie@gmail.com](mailto:pirvanescudimitrie@gmail.com) or see the [support page](../).
