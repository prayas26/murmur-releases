# Murmur — downloads

Push-to-talk dictation for macOS. Hold a shortcut, speak, release — the text
appears at your cursor in whatever app you're using.

**[Download the latest release →](https://github.com/prayas26/murmur-releases/releases/latest)**

Open the `.dmg` and drag Murmur to Applications. The app and the disk image are
both notarized by Apple and stapled, so it opens with a double-click — no
right-click → Open, and no network round-trip on first launch.

Requires macOS 14 or later.

## What it does

Transcription runs on-device via Apple's Speech framework. Audio never leaves
your Mac and is deleted as soon as it's transcribed. There is no backend and no
account.

Cleanup — dropping filler words, repairing punctuation — is on-device by default
too, using Apple Intelligence. You can point it at a cloud model instead with
your own API key, in which case Settings says plainly that the text is leaving
the machine.

Murmur checks this repository about once a day for a newer version number. It
never installs anything on its own, and the check can be switched off.

## This repository

Downloads only — the source is not published here. Releases carry the built,
signed and notarized disk image, and nothing else lives in this repo.
