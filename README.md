# Unbloat

Remove the apps that came pre-installed on your Android phone: no computer, no root, no other app needed.

Unbloat lists every app on your phone. Select the ones you don't want, tap **Delete**, and they're gone together
with their data. Changed your mind? Pre-installed apps you deleted can be brought back from the **Deleted** tab.

Available in English and Arabic (العربية).

## Download

**[Download the latest version](https://github.com/zakariaadem/Unbloat-releases/releases/latest)**: on that
page, tap the `.apk` file under **Assets**.

This page only hosts the app downloads. Unbloat's source code isn't public.

## Requirements

- Android 11 or newer
- Wi-Fi (Unbloat uses your phone's own *Wireless debugging*; nothing is sent over the network)

## Installing

1. Download the `.apk` file on your phone and open it.
2. If Android asks, allow your browser or file manager to install apps.
3. **Google Play Protect may warn that Unbloat could be harmful.** It warns about apps it hasn't seen
   before, especially ones that use debugging access, which Unbloat needs in order to remove pre-installed
   apps. Choose to install anyway if you trust this download.

## Setting up (once, about two minutes)

Open Unbloat and tap the **?** button for a step-by-step guide. In short:

1. Turn on **Developer options**: Settings > About phone > tap **Build number** 7 times.
2. Connect to **Wi-Fi**.
3. In Unbloat, tap **Start pairing**. Turn on **Wireless debugging**, tick **Always allow on this network**,
   and tap **Pair device with pairing code**.
4. Type the 6-digit code into Unbloat's notification.

After that, Unbloat reconnects by itself, even after a restart.

## Updating

Download the newest `.apk` from the [latest release](https://github.com/zakariaadem/Unbloat-releases/releases/latest)
and install it over your current version. Your settings and pairing are kept.

## Use at your own risk

Unbloat can remove almost anything, including core parts of Android. Apps marked **Risky** (like System UI,
Settings or your home screen) can stop your phone from working properly, and fixing that may need a factory
reset. Unbloat warns you before deleting them, but the choice is yours.

Unbloat is provided as is, without any warranty. The author isn't responsible for any damage or data loss.

A factory reset always brings back every pre-installed app.

## Credits

Unbloat uses these open-source libraries:

- [Kadb](https://github.com/flyfishxu/Kadb) (Apache License 2.0)
- [Conscrypt](https://github.com/google/conscrypt) (Apache License 2.0)
- [Bouncy Castle](https://www.bouncycastle.org/) (MIT License)
- [AndroidX and Jetpack Compose](https://developer.android.com/jetpack) (Apache License 2.0)

© 2026 Zakaria Adam. All rights reserved.
