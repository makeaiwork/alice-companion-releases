# Alice Companion

A lightweight, unofficial macOS companion for Alice AI. Use your own Yandex account in a full desktop window or a compact panel at the edge of your screen.

[Download for macOS](https://github.com/makeaiwork/alice-companion-releases/releases/latest/download/Alice-Companion.dmg) · [Release notes](https://github.com/makeaiwork/alice-companion-releases/releases) · [Report an issue](https://github.com/makeaiwork/alice-companion-releases/issues)

## Requirements

- macOS 15 or later.
- Apple Silicon or Intel Mac. One universal installer supports both.
- An internet connection and your own Yandex account.

The app interface is currently in Russian. This repository contains public installers, release notes, and the signed Sparkle update feed. Application source code is private.

## Install

1. Download and open `Alice-Companion.dmg`.
2. Drag **Alice Companion** into **Applications**.
3. Open the app from Applications and sign in to Yandex.
4. Allow microphone access when you first choose to use voice.

The app and installer are Developer ID signed and notarized by Apple. Each release includes a SHA-256 checksum for the versioned installer.

## Features

- Full desktop chat and a compact companion attached to the screen edge.
- A draggable Alice launcher, monochrome menu-bar logo, and Dock icon.
- Configurable shortcuts for opening the companion and starting voice conversations.
- Voice activation by pressing a shortcut or holding it down.
- Translation, summaries, spelling correction, rewriting, question answering, shorter text, and longer text.
- Optional selection and screenshot capture, with a preview before sending.
- Website-owned Alice modes, files, history, and account access.

The default companion shortcut is **Option–Space**. The default voice shortcut is **Control–Option–Space**. Change them in Settings.

## Updates

Sparkle checks for updates at launch and every six hours when automatic checks are enabled. You can also choose **Check for Updates** from the app menu or Settings. Update descriptions include changes from versions you skipped.

Both the update feed and installers use cryptographic signatures. Install the app in Applications before updating; do not run it permanently from the disk image.

## Privacy and permissions

Alice Companion loads the Alice website directly. It does not send conversations through a separate companion server. Yandex handles your account and AI requests under its own terms and privacy policy.

Microphone and camera access require macOS permission. Selection capture may require Accessibility permission; screenshot capture may require Screen Recording permission. These features are optional.

Text tools add an instruction to the message sent to Alice. The companion displays the original text and a tool badge, but the complete instruction can remain visible in other clients or shared conversations.

## Troubleshooting

If chat or voice is unavailable, check whether the same feature works on the [Alice website](https://alice.yandex.ru/). Some failures are caused by service availability rather than the desktop app.

When reporting an issue, include your macOS version, Mac architecture, app version, and steps to reproduce it. Do not post credentials, private conversations, or unredacted screenshots containing personal information.

## Acknowledgments

Alice and Yandex are trademarks of their respective owners. This application is unofficial and is not affiliated with or endorsed by Yandex.

The app uses [Sparkle](https://sparkle-project.org/) for updates and [Lucide](https://lucide.dev/) icons. Third-party license notices are bundled with the application.
