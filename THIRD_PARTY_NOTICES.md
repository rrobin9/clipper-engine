# Third-party software in Clipper Engine

Clipper Engine is free to use. It is built on the open-source projects below, which keep
their own licences. Nothing here is affiliated with Rockstar Games, Take-Two, Twitch or
YouTube.

## FFmpeg (GPL)

The app ships a separate `ffmpeg` program (version 9.0, from the `imageio-ffmpeg` 0.8.1
package) that records, cuts and encodes video. That build is configured with `--enable-gpl`
(it includes x264, libass and FreeType), so **this ffmpeg program is licensed under the GNU
General Public License, version 3 or later**. Clipper Engine runs it as its own process; it
is not linked into the app's code.

- Licence: https://www.gnu.org/licenses/gpl-3.0.html
- Source code of FFmpeg 9.0: https://ffmpeg.org/releases/ (and https://git.ffmpeg.org/ffmpeg.git)
- Where this binary comes from: https://github.com/imageio/imageio-ffmpeg and
  https://github.com/imageio/imageio-binaries
- On request, the maintainer of this app will provide the exact source code of the bundled
  ffmpeg for at least three years: open an issue at https://github.com/rrobin9/clipper-engine.

## Python and the libraries the app is made of

| Project | Licence |
|---|---|
| Python 3.12 | PSF License |
| streamlink | BSD-2-Clause |
| yt-dlp | Unlicense |
| faster-whisper, CTranslate2, the Whisper "small" model (downloaded on first use) | MIT |
| ONNX Runtime | MIT |
| tokenizers, huggingface-hub | Apache-2.0 |
| PyAV (`av`; its wheels bundle FFmpeg libraries under the LGPL) | BSD-3-Clause |
| OpenCV (opencv-python-headless) | Apache-2.0 |
| NumPy | BSD-3-Clause and others |
| FastAPI, Pydantic, httptools, watchfiles | MIT |
| Starlette, uvicorn, websockets | BSD-3-Clause |
| PyYAML | MIT |
| PyInstaller (packs the app; its bootloader exception lets any app use it) | GPL-2.0-or-later with the bootloader exception |

## The app's screens

Preact, @preact/signals and three.js (MIT); the fonts Barlow, Barlow Condensed and Mr Dafoe
(SIL Open Font License 1.1). Their full licence texts are in the app at `/licenses.txt`.
The caption fonts and their licences are in `clipper/assets/fonts/`.
