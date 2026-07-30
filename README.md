# Sound-To-Haptics

Sound-To-Haptics is an Android application that converts MP3 audio into immersive haptic feedback by generating Android-compatible haptic audio files.

# Disclaimer 

Please do not use any type of music/audio that has heavy bass drops or alot of overlapping beats, it could cause major damages to your device's haptic motor. If you do not follow this then any damage caused to your device is completely on you and not on the application nor the creator. You have been warned.

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

# Supported Haptic-Enabled Devices

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
- Pixel 10
- Pixel 10 Pro
- Pixel 10 Pro XL
- Pixel 10 Pro Fold

Samsung

### Galaxy S Series

- Galaxy S21
- Galaxy S21+
- Galaxy S21 Ultra
- Galaxy S22
- Galaxy S22+
- Galaxy S22 Ultra
- Galaxy S23
- Galaxy S23+
- Galaxy S23 Ultra
- Galaxy S24 *(tested)*
- Galaxy S24+
- Galaxy S24 Ultra
- Galaxy S25
- Galaxy S25+
- Galaxy S25 Ultra
- Galaxy S26
- Galaxy S26+
- Galaxy S26 Ultra

**ANY SAMSUNG FE EDITION WILL NOT WORK**

### Galaxy Z Series

- Galaxy Z Fold3
- Galaxy Z Fold4
- Galaxy Z Fold5
- Galaxy Z Fold6
- Galaxy Z Fold7
- Galaxy Z Flip3
- Galaxy Z Flip4
- Galaxy Z Flip5 *(tested)*
- Galaxy Z Flip6
- Galaxy Z Flip7

### Galaxy A Series

- Galaxy A55 *(limited)*
- Galaxy A56 *(limited)*

### Galaxy XCover

- Galaxy XCover7 *(limited)*

---

OnePlus

- OnePlus 9 *(limited)*
- OnePlus 9 Pro
- OnePlus 10 *(limited)*
- OnePlus 10 Pro
- OnePlus 10T *(limited)*
- OnePlus 11
- OnePlus 12
- OnePlus 12R *(limited)*
- OnePlus 13
- OnePlus 13R *(limited)*
- OnePlus Open

---

OPPO

- Find X5 *(limited)*
- Find X5 Pro
- Find X6 *(limited)*
- Find X6 Pro
- Find X7
- Find X7 Ultra
- Find X8
- Find X8 Pro
- Find X8 Ultra
- Find N3
- Find N5

---

vivo

- X90 *(limited)*
- X90 Pro
- X90s
- X100
- X100 Pro
- X100 Ultra
- X200
- X200 Pro
- X200 Ultra
- X Fold3
- X Fold3 Pro

---

Xiaomi

- Xiaomi 12 *(limited)*
- Xiaomi 12 Pro
- Xiaomi 13
- Xiaomi 13 Pro
- Xiaomi 13 Ultra
- Xiaomi 14
- Xiaomi 14 Pro
- Xiaomi 14 Ultra
- Xiaomi 15
- Xiaomi 15 Pro
- Xiaomi 15 Ultra
- MIX Fold 3
- MIX Fold 4
- MIX Flip

### Redmi

- Redmi K60 Pro
- Redmi K70
- Redmi K70 Pro
- Redmi K80
- Redmi K80 Pro

### POCO

- POCO F5 Pro
- POCO F6
- POCO F6 Pro
- POCO F7
- POCO F7 Pro
- POCO F7 Ultra

---

ASUS

- Zenfone 10
- ROG Phone 6
- ROG Phone 6 Pro
- ROG Phone 7
- ROG Phone 7 Ultimate
- ROG Phone 8
- ROG Phone 8 Pro
- ROG Phone 9
- ROG Phone 9 Pro

---

Sony

- Xperia 1 III
- Xperia 1 IV
- Xperia 1 V
- Xperia 1 VI
- Xperia 5 III
- Xperia 5 IV
- Xperia 5 V
- Xperia 10 V *(limited)*
- Xperia 10 VI *(limited)*

---

Motorola

- Edge 30 Ultra
- Edge 40 *(limited)*
- Edge 40 Pro
- Edge 50 Pro
- Edge 50 Ultra
- Edge 60 Pro
- Razr 40 Ultra
- Razr 50 Ultra
- Razr 60 *(limited)*
- Razr 60 Ultra

---

HONOR

- Magic4 Pro
- Magic5 Pro
- Magic5 Ultimate
- Magic6 Pro
- Magic6 Ultimate
- Magic7 Pro
- Magic V2
- Magic V3
- Magic Vs
- Magic V Flip

---

Nothing

- Phone (1)
- Phone (2)
- Phone (2a)
- Phone (3)
- Phone (3a)
- Phone (3a Pro)

### CMF

- CMF Phone 1 *(limited)*

---

realme

- GT 2 Pro
- GT 5 Pro
- GT 6
- GT 7
- GT 7 Pro

---

iQOO

- iQOO 11
- iQOO 12
- iQOO 13
- iQOO Neo9 Pro
- iQOO Neo10 Pro

---

nubia

- Z60 Ultra
- Z70 Ultra
- RedMagic 8 Pro
- RedMagic 9 Pro
- RedMagic 10 Pro

---

Meizu

- Meizu 20 Pro
- Meizu 21
- Meizu 21 Pro

---

Lenovo

- Legion Y90

---

Sharp

- AQUOS R8
- AQUOS R9

> **Note:** Devices marked ***(limited)*** may not have the X-axis linear motors or may have OEM restrictions that reduce advanced haptic playback quality. They should still support Android haptic APIs, but results may vary compared to flagship devices.


# Credits

Without these, this wouldn't be possible.

HapticLabs Kotlin Library
FFMPeg Library

# Q&A

**Will this be open-sourced soon?**
Yes, soon I have to adjust some code so it is more understandable.

