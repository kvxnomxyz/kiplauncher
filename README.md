# KiP-Launcher
A launcher fix for Knowledge is Power app(s)
> DISCLAIMER | i dont know the technical reason for the crashes :p only came out with the fix

## The problem itself

The app Knowledge is Power (ill refer as KiP) breaks at the Android 13/14 point, and NO ONE knws why

## The Fix

The fix is actually simple:
By installing KiP and running it with `adb logcat -c && adb shell monkey -p com.playstation.knowledge 1 && adb logcat -d -b crash > ~/Work/kip_new_fix/crash.log` it dumps a log. BUT when i ran it with this command and spammed it several times more whilst it being at the TITLE SCREEN is actually worked and launched the app. A test-play confirmed thw orking of the fix.
Here is a video:

https://github.com/user-attachments/assets/16022ca7-d773-4068-9ffe-fa0b006e3411

## What is the launcher ACTUALLY doing?
just spamming the command but locally its so simple bruh
