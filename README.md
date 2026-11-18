<p align="center"><img src="images/icon.png" width="144" alt="Afterglow app icon"></p>

# Afterglow for Mac

**Keep your Mac awake. Give your screens somewhere to wander.**

[Download Afterglow for Mac](https://github.com/keegan-wang/afterglow-downloads/releases/latest/download/Afterglow.dmg) ·
[All releases and ZIP downloads](https://github.com/keegan-wang/afterglow-downloads/releases)

macOS 14 or later · Apple Silicon + Intel · Runs offline

**Public beta — not yet notarized by Apple.** macOS may require explicit approval
on first launch. See the installation instructions below before downloading.

![Afterglow scenes](images/scenes.png)

## Animated scenes and video wallpapers

- **Three full-motion video wallpapers, included:** Redwood, a forest creek;
  Golden Coast, an animated impressionist California sunset with sailboats;
  and Willow Pond, a cozy woodland cottage with ducks, rain, and rippling water.
- **Six procedural scenes:** Aurora, Tides, Orbit, Starfield, Rain, and Clock.
- **Your own videos:** optionally replace a video scene with a local MP4, MOV,
  or M4V. All built-in wallpapers work immediately and offline.

The three video scenes use AI-generated artwork and video. Each monitor plays
its own full-frame movie loop through the native macOS video player. Artwork was
created with OpenAI image generation; videos were generated locally with
[Lightricks LTX-Video](https://huggingface.co/Lightricks/LTX-Video). Willow Pond's
woodland-water direction was inspired by [Daniil Ch.'s Quack demo](https://x.com/daniildesigns/status/2122798311279108476).

![Willow Pond video preview](images/willow-pond.gif)

Click **Start screensaver** to cover every connected display and prevent idle
sleep. Move the mouse or press a key to return to your desktop; the awake session
continues until you stop it or its timer ends. Keep the laptop lid open.

Afterglow has menu-bar controls, timed sessions, low energy animation, and support
for Reduce Motion. It has no account, analytics, network requests, or runtime
downloads. Your existing macOS lock settings remain in force; the visual
screensaver is not a password lock.

## Install

1. Download and open **Afterglow.dmg**.
2. Drag **Afterglow.app** to **Applications**.
3. Open it from Applications, choose a scene, and click **Start screensaver**.

This beta is ad-hoc signed, **not Developer ID signed or Apple notarized**. If
macOS blocks it, only proceed if you trust the download. Apple's documented
per-app approval is **System Settings → Privacy & Security → Open Anyway**, after
you first try to open the app. See [Apple's instructions](https://support.apple.com/en-us/102445).

Developer ID signing and notarization are planned for a future build. There is no
need to disable Gatekeeper or change system-wide security settings.

For updates, quit Afterglow before replacing it in Applications. Download checksums
are included as `SHA256SUMS.txt` with each release.

## Feedback

[Report a problem or request a scene](https://github.com/keegan-wang/afterglow-downloads/issues).
This repository hosts the app, artwork previews, and releases. Application source
is maintained separately.

Copyright © 2026 Keegan Wang. MIT license.
