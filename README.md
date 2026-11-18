# Clipper Engine: clip GTA 6 streams automatically (free)

Clipper Engine finds the hottest live GTA 6 streams on **Twitch and YouTube** and clips every
hype moment for you, in **widescreen and vertical 9:16, with captions**. It runs on your own
computer: **free, no account, no login.**

**Try the live preview first:** https://clipperengine.vercel.app

## Download

| Your computer | Download |
|---|---|
| **Mac** (Apple Silicon: M1 and newer, macOS 14 or newer) | [Clipper-Engine-mac-arm64.zip](https://github.com/rrobin9/clipper-engine/releases/latest/download/Clipper-Engine-mac-arm64.zip) |
| **Windows** (10 and 11, 64-bit) | [Clipper-Engine-windows-x64.zip](https://github.com/rrobin9/clipper-engine/releases/latest/download/Clipper-Engine-windows-x64.zip) |

## Install

**Mac**
1. Unzip and drag **Clipper Engine** into **Applications**, then open it.
2. The first time, macOS may say it can't check the app (it is not from the App Store). Open
   **System Settings → Privacy & Security**, scroll down and press **Open Anyway**.
3. Your browser opens the app. In Chrome or Edge, press **Install** in the address bar to give
   it its own window and icon.

**Windows**
1. Unzip the folder somewhere you keep apps (for example Documents) and open **Clipper Engine.exe**.
2. If a blue "Windows protected your PC" box appears, press **More info → Run anyway**
   (the app is new and not code-signed, not unsafe).
3. Your browser opens the app. In Chrome or Edge, press **Install** for its own window.

## How it works

- **Stream Dashboard:** the busiest live streams right now, ranked by how fast chat is moving,
  and the GTA 6 streams coming up next. Add your own streams by name or link.
- **Clipper Engine:** press start and it records the best streams and clips every moment the
  chat explodes. **Clip it now** finds the best moment of the last 3 minutes, or takes the last
  15 s to 2 min; **Mark start / Mark end** clips exactly what you marked.
- **Clip Garage:** every clip in widescreen and 9:16 with captions. Trim, switch the layout,
  approve, copy title and hashtag ideas, export for TikTok, Reels and Shorts.

The first time, the captions model (about 500 MB) downloads by itself; clips are made in the
meantime. Clips are saved in **Movies/Clipper Engine** (Mac) or **Videos\Clipper Engine** (Windows).

## Is it safe?

- The app only listens on your own computer (`http://localhost:7377`); other devices and
  websites cannot use it.
- No account, no tracking, no ads. It only connects to Twitch and YouTube to watch the public
  streams you record (and once to download the captions model).
- It is not code-signed (that costs a yearly fee), so Mac and Windows warn the first time.
  You can check that your download is the real one: the
  [release page](https://github.com/rrobin9/clipper-engine/releases/latest) lists the SHA-256
  of every file. On a Mac: `shasum -a 256 Clipper-Engine-mac-arm64.zip`. On Windows:
  `certutil -hashfile Clipper-Engine-windows-x64.zip SHA256`.

## Good to know

- Clip responsibly: each clip credits the streamer on screen; follow each platform's rules and
  the streamers' wishes when you post.
- Not affiliated with Rockstar Games, Take-Two Interactive, Twitch or YouTube.
- Free to use, provided as is, without warranty.
- Third-party software and licences, including the GPL notice for the bundled ffmpeg:
  [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Something not working? [Open an issue](https://github.com/rrobin9/clipper-engine/issues).
