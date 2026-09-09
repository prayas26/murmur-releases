# Murmurly — downloads

Push-to-talk dictation for macOS. Hold a key you choose, speak, let go — the words
land at your cursor in whatever app you're using.

**[Download Murmurly.dmg →](https://github.com/prayas26/murmur-releases/releases/latest/download/Murmurly.dmg)**
· [murmurly.prayasmittal.com](https://murmurly.prayasmittal.com)

Open the disk image and drag Murmurly to Applications. The app and the image are both
notarized by Apple and stapled, so it opens with a double-click and needs no network
on first launch.

Requires macOS 14 or later.

## Coming from Murmur 1.10

Murmur is now Murmurly. This is a fresh install rather than an update: the updater in
1.10 can't install it, and macOS will ask for the microphone, speech and Accessibility
permissions again. Your history and statistics carry over.

## What it does, and where your words go

Transcription runs on-device with Apple's speech recognizer. Audio never leaves your
Mac and is discarded as soon as it's transcribed. Cleanup — dropping filler words,
adding punctuation — runs on-device too, with Apple Intelligence. You can point it at a
cloud model with your own API key instead, and Settings says plainly that the text
leaves the machine when you do.

Murmurly asks you to sign in with Google once. After that it sends usage counts — how
many dictations, how many words, which features — and never any text; the server has
no field that could hold one. Signing in is the only thing that needs the internet.

It checks this repository about once a day for a newer version. It never installs
anything on its own, and the check can be switched off.

## This repository

Downloads only — the source is not published here. Releases carry the built, signed and
notarized disk image, and nothing else lives in this repo.
