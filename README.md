# Overview

Native plugin for Unity for iOS and Android.
Use custom vibrations on mobile.

Reference: "https://github.com/BenoitFreslon/Vibration", "https://gist.github.com/ruzrobert/d98220a3b7f71ccc90403e041967c46b"

# Installation

1. Open the Package Manager from Window > Package Manager.
2. Click the "+" button > Add package from git URL.
3. Enter the following URL:

```
https://github.com/lazycoder71/LazyCoder.Haptic.git
```


# Use

## Initialization

Initialize the plugin with this line before using vibrations:

`Haptic.Init();`

## Vibrations

Just call `Haptic.Vibrate(HapticType type);`

## Enable/Disable

Set `Haptic.Enable` to true or false.