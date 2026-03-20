<div align="center">
  <h6>macOS → Read the <a href="#installation">installation</a> guide or the app won't launch.</h6>
  <br>
  <picture>
    <source width="128" height="128" alt="Resonance Dark" media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/84bee56e-6005-41c6-b2d8-a2ef82250a4d" />
    <source width="128" height="128" alt="Resonance Light" media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/8e0a5431-91c4-4a47-9233-79d3998de15c" />
    <img alt="Resonance" src="https://github.com/user-attachments/assets/fbcbfaa8-9d82-4ae0-b2ec-7ec7bfc76bf3" />
  </picture>
  <h3>Resonance</h3>
  A lightweight local music player inspired by the golden era of classic desktop players.
  <br><br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/c1617d50-0807-4ea4-98da-9789e2b0fc16" />
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/6fa27488-6768-400f-9105-ce64ba52faaa" />
  </p>
</div>

## No Subscriptions. No Algorithm Nonsense.

Remember when software had a soul?  
When your music player didn't track you, feed you algorithms, or charge $120 a year to play songs you don't own?

**Resonance** aims to bring back what listening to music is really about.  
Just you, your music library, and a skeuomorphic interface inspired by the golden age of desktop apps.

All shipped as a simple, portable audio player. **Own your music. Own your experience.**

## Supported Audio Formats

All major formats are supported. Not sure which to use? Refer to this cheat sheet.

| Format | Type | License | Usage |
|--------|------|---------|-------|
| MP3 | Lossy | Public Domain | Daily |
| AAC | Lossy | Apple | Daily |
| ALAC | Lossless | Apple | Enthusiasts |
| AIFF | Lossless | Apple | Enthusiasts |
| FLAC | Lossless | Open | Enthusiasts |
| WAV | Lossless | Microsoft | ⚠ Production / DAW |
| OGG | Lossy | Open | ⚠ Not recommended |
| Opus | Lossy | Open | ⚠ Not recommended |

## Features

Browse your library, hit play instantly, and enjoy a clean, nostalgic experience.

- **Instant Playback** - Load your library and play immediately.
- **Full Controls** - Play, pause, skip, shuffle, and loop.
- **Volume Control** - Adjust volume, pan, or mute anytime.
- **Equaliser** - Fine-tune frequencies to your taste.
- **Mini Mode** - Compact player for quick access.
- **Skeuomorphic Design** - 2000s vibes, because flat design is boring.
- **Lightweight** - Minimal footprint, runs on modest hardware.
- **Zero Tracking** - Your listening habits stay yours.
- **100% Local** - No internet, no data collection.

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/4c20e612-9501-48bc-b418-0b4f4def8185"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/898fe7fb-d9ff-4d9f-bc7b-b44dbd484b4f" />
  </p>
</div>

## Requirements

RAM is kind of expensive right now... Performance is monitored before every update.

- **~100 MB** of RAM for 1,000+ songs.
- **~300 MB** of RAM and an SSD are recommended for large libraries of +10,000 songs.

That said, the app is lightweight enough to probably run on your smart refrigerator.

## Installation

Download the [latest version](https://github.com/Oxen-Studio/Resonance/releases/latest) for your operating system and follow the instructions below.

### Apple Silicon

Stable on Apple Silicon Macs running macOS Big Sur 11.0 or later.

| | Version | Status |
|-|---------|--------|
| <img width="16" height="16" alt="macOS Tahoe" src="https://github.com/user-attachments/assets/80988eeb-a80a-4aaf-ad75-3e9cdf49f463" /> | macOS Tahoe `latest` | Tested ✓ |
| <img width="16" height="16" alt="macOS Sequoia" src="https://github.com/user-attachments/assets/a37f9973-a739-4bc0-8a7e-3f50255ac39e" /> | macOS Sequoia | Tested ✓ |

1. Extract [Resonance_mac.zip](https://github.com/Oxen-Studio/Resonance/releases/latest/download/Resonance_mac.zip).
2. Open <img width="16" height="16" alt="Terminal" src="https://github.com/user-attachments/assets/d9009a5b-9cf8-4253-899c-50f933442cfc" /> **Terminal**, press `⌘ Space`, type **Terminal** and hit `Enter`.
3. Type the following command and hit `Enter`. Replace `Downloads` with the folder where you saved the app:
```
   cd Downloads
```
4. Run this command and hit `Enter`:
```
   xattr -dr com.apple.quarantine Resonance.app
```
5. Double-click the app to launch it, or move it to your `Applications` folder for quick access via **Spotlight**.

### Windows

Stable on PCs running Windows 10 or later.

| | Version | Status |
|-|---------|--------|
| <img width="16" height="16" alt="Windows 11" src="https://github.com/user-attachments/assets/81994aa0-9917-4653-8d97-d0d7e0d93521" /> | Windows 11 `latest` | Tested ✓ |
| <img width="16" height="16" alt="Windows 10" src="https://github.com/user-attachments/assets/2411022e-fa87-41f3-bb62-8f63b0476017" /> | Windows 10 | Tested ✓ |

1. Download and extract [Resonance_win_exe.zip](https://github.com/Oxen-Studio/Resonance/releases/latest/download/Resonance_win_exe.zip).
2. Double-click `Resonance.exe` to launch it.
3. Click `More info` then `Run anyway` if <img width="16" height="16" alt="Windows Defender" src="https://github.com/user-attachments/assets/d7544da1-b84e-4591-80d5-e5a12e454714" /> **Windows Defender** warns you.

An [installer version](https://github.com/Oxen-Studio/Resonance/releases/latest/download/Resonance_win_install.zip) is also available.

### Linux

*Scheduled for the next major update.*

### Why the Extra Steps?

> [!NOTE]
> **Resonance** is a passion project not signed with an Apple Developer or Windows Store certificate. macOS and Windows will show a security warning as a result. The steps above safely bypass it.

## Q&A

<details open>
<summary><h3>How do I load music?</h3></summary>

- <b>Drag & drop</b> or click the <b>folder icon</b> and select your music folder.
  - Choose your entire library; full folder trees are supported.
  - Tested on an M1 Pro: a 4-level folder structure with <b>903 tracks</b> loads in <b>~1.16 seconds</b>.

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/a6a1dfef-c087-436e-89c4-07a22e447951"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/c75d487e-9485-4198-b72f-3a26aa391147" />
  </p>
</div>

</details>

<details open>
<summary><h3>How do I minimize the app?</h3></summary>

- Click the button <b>above the volume control</b> to enter Mini Mode.

</details>

<details open>
<summary><h3>The app disappeared. Help?!</h3></summary>

- Click the <b>middle-right edge of your screen</b> (about an inch from the screen border).

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/ebd0ed64-1f45-4d03-ae7c-6221108e5dbc"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/a3b64e3c-8a41-4296-a532-1bcdb1867724" />
  </p>
</div>

</details>

<details open>
<summary><h3>I want to prevent the app from disappearing</h3></summary>

- Click the <b>lock icon</b> to pin the app in place.

</details>

## Roadmap

#### Tracklist & Library
- [x] Song title, artist, album art & details
- [x] Bitrate & sample rate
- [x] Codec display
- [x] Multi-folder support
- [ ] Drag & drop file support

#### Playback
- [x] SFX sounds
- [ ] Gapless playback
- [ ] OS media controls *(play, pause, skip via keyboard / system)*

#### Equaliser
- [x] Basic EQ controls
- [x] Presets
- [x] Left / right balance
- [x] Custom preset saving
- [ ] Pitch & speed

#### Visualizer
- [x] Simple visualizer
- [ ] Old-school visualizer

#### Library & Playlists
- [ ] Playlist support *(create, edit, reorder)*

#### Metadata
- [ ] ID3 tag editor

#### Advanced
- [ ] Transcoder / remuxer
- [ ] Skin support
- [ ] Play counter
- [ ] Last.fm integration
- [ ] Automatic updates

## Contributing

We value every contribution and carefully read every message, commit, and issue.

- Open an issue for bugs or feature requests.
- Share feedback on [Reddit](https://reddit.com/r/ResonanceApp/).
- Got an idea for a custom skin? Let us know.
- Need a music management tool? Check out [Oxen Converter](https://github.com/Oxen-Studio/oxen-converter).

## Philosophy

Technology used to be cool.  
Your music player didn't spy on you.  
The internet wasn't five websites in a trench coat.

Resonance isn't trying to kill Spotify. **It's just giving you back what you lost.**

---

Powered by [React](https://react.dev) and [Tauri](https://v2.tauri.app/).

###### © Oxen Studio
