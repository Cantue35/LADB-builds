<p align="center">
    <a href="https://play-lh.googleusercontent.com/e1lEjVH1cjZFjyKGymB3HprppThMBnZlfi51z7alJm5wpTzWHNG2WWOlROs_vp-sQb7a=s128">
        <img src="https://play-lh.googleusercontent.com/e1lEjVH1cjZFjyKGymB3HprppThMBnZlfi51z7alJm5wpTzWHNG2WWOlROs_vp-sQb7a=s128" />
    </a>
</p>

<h1 align="center">LADB</h1>

<h4 align="center">A local ADB shell for Android!</h4>

## Overview

LADB is a local ADB shell for Android that enables wireless ADB debugging. It allows you to interact with your Android device's ADB server over a local connection.

## How It Works

LADB bundles an ADB server within the app libraries. Normally, this server cannot connect to the local device because it requires an active USB connection. However, Android's Wireless ADB Debugging feature allows the server and the client to speak to each other locally.

## Initial Setup

To get started with LADB, follow these steps:

1. Use split-screen mode or a pop-out window with LADB and Android Settings at the same time. This is important because Android will invalidate the pairing information if the dialog gets dismissed.
2. Add a Wireless Debugging connection in Android Settings.
3. Copy the pairing code and port from Android Settings into LADB.
4. Keep both windows open until the Android Settings dialog dismisses itself.

## Issues

Please note that LADB is currently incompatible with Shizuku. If you have Shizuku installed, LADB may fail to connect properly. You must uninstall Shizuku and reboot your device to use LADB successfully.

GitHub Actions builds are maintained in this fork by [Cantue35](https://github.com/Cantue35) for personal use only.
**These builds are not intended for Play Store publishing or wide redistribution.**


## Troubleshooting

If you encounter any issues with LADB, consider the following steps:

- Clear the app data for LADB.
- Remove all Wireless Debugging connections from Android Settings.
- Reboot your device.

# License

The license is mostly permissive other than it does not allow unofficial builds to be released to the Google Play Store.

## Support
If you find LADB useful and would like to support the developer, consider purchasing the application from [Google Play](https://play.google.com/store/apps/details?id=com.draco.ladb).

If you have questions or need assistance, you can contact the author via email at tylernij+LADB@gmail.com.

There is also a Telegram server available for support: [LADB Support](https://t.me/ladb_support).

## Privacy Policy

LADB respects your privacy and does not send any device data outside the app. Your data is not collected or processed.