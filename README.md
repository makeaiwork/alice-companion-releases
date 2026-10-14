# AliceMate

A lightweight, unofficial macOS companion for Alice AI. Use your own Yandex account in a full desktop window or a compact panel at the edge of your screen.

[Download for macOS](https://github.com/makeaiwork/alice-companion-releases/releases/latest/download/AliceMate.dmg) · [Release notes](https://github.com/makeaiwork/alice-companion-releases/releases) · [Report an issue](https://github.com/makeaiwork/alice-companion-releases/issues)

## Requirements

- macOS 15 or later.
- Apple Silicon or Intel Mac. One universal installer supports both.
- An internet connection and your own Yandex account.

The app interface is currently in Russian. This repository contains public installers, release notes, and the signed Sparkle update feed. Application source code is private.

## Install

1. Download and open `AliceMate.dmg`.
2. Drag **AliceMate** into **Applications**.
3. Open the app from Applications and sign in to Yandex.
4. Allow microphone access when you first choose to use voice.

The app and installer are Developer ID signed and notarized by Apple. Each release includes a SHA-256 checksum for the versioned installer.

## Features

- Full desktop chat and a compact companion attached to the screen edge.
- A draggable Alice launcher, monochrome menu-bar logo, and Dock icon.
- Configurable shortcuts for opening the companion, voice conversations, and message dictation.
- Press-to-toggle voice conversations and optional toggle or hold-to-dictate shortcuts.
- Translation, summaries, spelling correction, rewriting, question answering, shorter text, and longer text.
- Region screenshots attach directly to the current chat draft. Sending remains explicit; failed attachments can be retried or saved.
- Website-owned Alice modes, files, history, and account access.

The default companion shortcut is **Option–Space**. The default conversation shortcut is a single tap of the **right Command** key. It needs **Input Monitoring**; until you grant it, **Control–Space** starts a conversation instead, or **Control–Option–Space** when macOS (input source switching) or another AliceMate shortcut already uses Control–Space. Dictation starts disabled; enable it and assign an independent shortcut in Settings. Releasing a held dictation shortcut stops recognition and leaves the text in the draft for you to send. Switching between voice actions stops the previous action first.

You can also assign a standalone **Command**, **Option**, **Control**, or **Shift** key.
Click the shortcut field, then press and release the modifier; left and right keys
are assigned separately. A standalone tap takes effect on release. Hold-to-dictate
starts after a short delay; another key or mouse click cancels the gesture.
Standalone global modifiers require **Privacy & Security → Input Monitoring**
permission for AliceMate. Settings opens that pane alongside a guide with
a draggable app icon and a Finder shortcut for adding the running app.
Regular shortcuts such as Option–Space do not need this permission.

## Updates

Sparkle checks for updates at launch and every six hours when automatic checks are enabled. You can also choose **Check for Updates** from the app menu or Settings. Update descriptions include changes from versions you skipped.

Both the update feed and installers use cryptographic signatures. Install the app in Applications before updating; do not run it permanently from the disk image.

## Privacy and permissions

AliceMate loads the Alice website directly. It does not send conversations through a separate companion server. Yandex handles your account and AI requests under its own terms and privacy policy.

Microphone and camera access require macOS permission. Screenshots require Screen Recording permission. These features are optional; the app provides permission status and recovery guidance. If Screen Recording is denied, a floating guide helps add the running app to System Settings. Granting permission does not automatically take a screenshot.

Text tools add an instruction to the message sent to Alice. The companion displays the original text and a tool badge, but the complete instruction can remain visible in other clients or shared conversations.

## Troubleshooting

If chat or voice is unavailable, check whether the same feature works on the [Alice website](https://alice.yandex.ru/). Some failures are caused by service availability rather than the desktop app.

When reporting an issue, include your macOS version, Mac architecture, app version, and steps to reproduce it. Do not post credentials, private conversations, or unredacted screenshots containing personal information.

## Acknowledgments

Alice and Yandex are trademarks of their respective owners. This application is unofficial and is not affiliated with or endorsed by Yandex.

The app uses [Sparkle](https://sparkle-project.org/) for updates and [Lucide](https://lucide.dev/) icons. Third-party license notices are bundled with the application.
