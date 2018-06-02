# OreoTintRemover

One of the most foolish things I found immediately after upgrading from Nougat to Oreo (Android 8.1) is that
they paint my wallpaper like a sh*t! Surprise, that's the new [feature][1] of cool Android!

Well, let's fix the "feature":

1. Get rooted
2. Install [Xposed Framework][2]
3. Install [OreoTintRemover][3]
4. Enable the module in Xposed Installer
5. Reboot

## Build

```
./gradlew assembleDebug
```

## License

(The WTFPL)

[1]: https://www.androidpolice.com/2017/10/26/android-8-1-feature-spotlight-wallpaper-based-themes-include-tinted-notification-power-menu-shadows-just-like-pixel-2/
[2]: http://dl-xda.xposed.info/framework/sdk27/
[3]: http://repo.xposed.info/module/moe.banana.mods.notint
