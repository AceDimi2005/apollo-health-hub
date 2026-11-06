---
title: Support
---

# Apollo: Health Hub — Support

Apollo is the iPhone and Apple Watch app for **Apollo**, a self-hosted health data hub. Your training, nutrition, sleep, body metrics and recovery live on a server you run yourself (at home, on a NAS or on a VPS). The app connects only to the server address you enter.

## Contact

- Email: [pirvanescudimitrie@gmail.com](mailto:pirvanescudimitrie@gmail.com)
- Report a problem or ask a question: [open an issue](https://github.com/AceDimi2005/apollo-health-hub/issues/new)

We usually answer within a few days.

## Getting started

1. Run the Apollo server (Docker) on a computer, NAS or VPS.
2. Open the app and enter the server's address, for example `192.168.1.20:8080` or `apollo.example.com`. Use HTTPS when the server is reachable outside your home network.
3. Sign in, create the first account on a new server, or join with an invite from the person who runs it.

Want to look around first? Tap **Explore with sample data** on the first screen. Everything works offline with sample data; leave it from **Settings**.

## Frequently asked questions

**The app can't reach my server.** Check that the phone is on the same network (or that the server is reachable from the internet), that the address and port are right, and that iOS allowed Apollo to use the local network (Settings → Privacy & Security → Local Network).

**How do I sync Apple Health?** Settings → Apple Health → Sync from Apple Health, then allow the data types you want. Readings go to your own server; syncing again never creates duplicates.

**How do I use the Apple Watch app?** Install Apollo on the watch from the Watch app on your iPhone. It signs in automatically through your iPhone with its own token, which you can revoke on the server under Settings → Tokens.

**Where is my data stored?** Only on your Apollo server. See the [privacy policy](privacy/).

**How do I delete my account and data?** In the app: Settings → Delete account, then confirm with your password. Your Apollo server deletes the account and all of its data, and the app signs out on iPhone and Apple Watch. Signing out alone only removes the server address and token from your devices.
