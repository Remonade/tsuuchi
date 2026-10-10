# Tsuuchi

Tsuuchi (通知, "notification") replaces Windows' notification banners with its own popups: no animation, no sound unless you pick one, and a look you choose.

## Features

- Colors, font, size and shape of the popups, with a live preview
- Settings per application, and per site for browser notifications
- One action per mouse button: close, open, pin, copy, close all, mute
- Notifications wait while a game or a video is fullscreen, instead of being lost
- Multi-monitor: popups go to the screen you pick
- English and French; other languages can be added as a JSON file

## Install

Download `Tsuuchi-win-Setup.exe` from the [latest release](https://github.com/Remonade/tsuuchi/releases/latest) and run it. No administrator rights needed, and updates install themselves.

The installer isn't signed: on the SmartScreen warning, click "More info", then "Run anyway".

Requires Windows 10 (version 2004 or later) or Windows 11. Windows should hide its own banners (Focus assist on "Alarms only", Do not disturb on Windows 11); Tsuuchi offers to set it at startup.

## Translating

Settings > General has a button that opens the languages folder. Copy `en.json`, rename it to your language code (`de.json`, `es.json`...) and translate the values. Open an issue with the file if you'd like it included.

## Credits

Sounds: Material Design by Google (CC BY 4.0) and Notifications by akx (CC0).
