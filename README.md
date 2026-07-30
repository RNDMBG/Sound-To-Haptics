# Sound-To-Haptics

Sound-To-Haptics is an Android application that converts MP3 audio into immersive haptic feedback by generating Android-compatible haptic audio files.

# Features

- Convert MP3 files into Android-compatible haptic tracks using the OGG Haptic support.
- Automatic audio conversion using FFmpeg.
- Synchronized haptic playback using the Haptics Labs Kotlin Library.

# How It Works

Sound-To-Haptics combines two libraries:

- FFmpeg converts MP3 audio into an OGG file while embedding the required "ANDROID_HAPTIC" metadata.
- The Haptics Labs Kotlin Library plays the generated haptic track alongside the audio, allowing compatible Android devices to reproduce synchronized tactile feedback.

# Device Compatibility

Sound-To-Haptics requires an Android device that supports Android's haptic playback framework.

# Requirements:

- Android device with a supported haptic actuator.
- Android version that supports haptic-enabled OGG playback (preferably Android 11 and up).

Compatibility depends on the manufacturer, I haven't been able to test every single device in this upcoming list, but from what I know these devices should work. The list bellow is carefully edited everyday to ensure it stays up-to-date.

# Supported Haptic-Enabled devices.

Google Pixel

- Pixel 6
- Pixel 6 Pro
- Pixel 6a
- Pixel 7
- Pixel 7 Pro
- Pixel 7a
- Pixel Fold
- Pixel Tablet
- Pixel 8
- Pixel 8 Pro
- Pixel 8a
- Pixel 9
- Pixel 9 Pro
- Pixel 9 Pro XL
- Pixel 9 Pro Fold

Samsung

Galaxy S Series

- Galaxy S21
- Galaxy S21+
- Galaxy S21 Ultra
- Galaxy S22
- Galaxy S22+
- Galaxy S22 Ultra
- Galaxy S23
- Galaxy S23+
- Galaxy S23 Ultra
- Galaxy S24 (tested)
- Galaxy S24+
- Galaxy S24 Ultra
- Galaxy S25
- Galaxy S25+
- Galaxy S25 Ultra
- Galaxy S26
- Galaxy S26+
- Galaxy S26 Ultra

Galaxy Z Series

- Galaxy Z Fold3
- Galaxy Z Fold4
- Galaxy Z Fold5
- Galaxy Z Fold6
- Galaxy Z Fold7
- Galaxy Z Flip3
- Galaxy Z Flip4
- Galaxy Z Flip5 (tested)
- Galaxy Z Flip6 
- Galaxy Z Flip7

OnePlus

- OnePlus 9 Pro
- OnePlus 10 Pro
- OnePlus 11
- OnePlus 12
- OnePlus 13
- OnePlus Open

OPPO

- Find X5 Pro
- Find X6 Pro
- Find X7
- Find X7 Ultra
- Find X8
- Find X8 Pro
- Find N3

vivo

- X90 Pro
- X100
- X100 Pro
- X200
- X200 Pro
- X Fold3
- X Fold3 Pro

Xiaomi

- Xiaomi 12 Pro
- Xiaomi 13
- Xiaomi 13 Pro
- Xiaomi 14
- Xiaomi 14 Pro
- Xiaomi 15
- Xiaomi 15 Pro
- MIX Fold 3
- MIX Fold 4

ASUS

- Zenfone 10
- ROG Phone 7
- ROG Phone 8
- ROG Phone 9

Sony

- Xperia 1 IV
- Xperia 1 V
- Xperia 1 VI
- Xperia 5 IV
- Xperia 5 V
- Xperia 10 VI

Motorola

- Edge 40 Pro
- Edge 50 Ultra
- Razr 50 Ultra
- Razr 60 Ultra

HONOR

- Magic5 Pro
- Magic6 Pro
- Magic7 Pro
- Magic V2
- Magic V3

Nothing

- Phone (1)
- Phone (2)
- Phone (2a)
- Phone (3)
- Phone (3a)
- Phone (3a Pro)
  

# Disclaimer

Please, and I mean PLEASE do not use music that has heavy bass drops or alot of overlapping beats, it could cause damage to the haptic motor. Any damage to any device is completely on you.

# YOU HAVE BEEN WARNED.


# Credits

Without these, this wouldn't be possible.

HapticLabs Kotlin Library
FFMPeg Library

#Q&A
**Will this be open-sourced soon?**
Yes, soon I have to adjust some code so it is more understandable.

