<div align="center">
  <h6>macOS → Read the <a href="#installation">installation</a> guide or the app won't launch.</h6>
  <br>
  <img width="96" height="96" alt="Resonance" src="https://github.com/user-attachments/assets/84bee56e-6005-41c6-b2d8-a2ef82250a4d" />
  <h3>Resonance</h3>
  Pure local music experience inspired by the golden era of classic desktop players.
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

## Supported Formats

All major formats are supported. Not sure which to use? Refer to this cheat sheet.

| Format | License | Notes |
|--------|---------|-------|
| `MP3` | Public Domain | Best for daily use |
| `AAC` | Apple | Best for daily use |
| `M4A` | Apple | Container for `AAC` or `ALAC` |
| `ALAC` | Apple | macOS only as standalone; Windows supported inside `M4A` |
| `AIFF` | Apple | macOS only |
| `FLAC` | Open | Best for enthusiasts |
| `WAV` | Microsoft | ⚠ Intended for production / DAW use |
| `OGG` | Open | ⚠ Not recommended |
| `Opus` | Open | ⚠ Not recommended |

## What's Inside

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

**No dependencies** required.

RAM is kind of expensive right now... Performance is monitored before every update.

- **~100 MB** of RAM for 1,000+ songs.
- **~200 MB** of RAM for large libraries of +10,000 songs.

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
3. Type the following command and hit Enter, replacing Downloads with the folder where the app is located:
```
   cd Downloads
```
For example, if it's in `Applications`:
```
   cd /Applications
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
Unfortunatly the Linux experience is not working out as intended (see the Other Distros part just below), and thus is considerated unstable, the app does have all it's features working but you might encounter some bad UX so beware (sorry).
#### Fedora
Download [Resonance_linux_x86_x64_rpm.zip](https://github.com/Oxen-Studio/Resonance/releases/latest/download/Resonance_linux_x86_x64_rpm.zip
)  and install it with the package manager like this:

```
dnf install ./Resonance-1.5.0-1.x86_64.rpm
```
### Other distros or if you still have problems
Since Resonance rely heavily webkitgtk, it's stability and performance is highly tied to it's version.
The problem is that currently most of the distro (debian/ubunut/linux mint) comes with old version of it, and these versions contains bugs that brokes the audio.
To fix that the hack is to run a container using a distro that is known to have less bugs:

1. Update your system
```
sudo apt update && sudo apt upgrade
```
2. Install distrobox
```
sudo apt install distrobox -y
```
3. Fetch and install the fedora 40 container (podman)

    > *Tested 39 to 45 and only the 40 is working correctly* 
```
distrobox create -n fedora -i fedora:40
```
4. Enter the container
```
distrobox enter fedora
```
5. Check that everything is up to date in it
```
sudo dnf update && sudo dnf upgrade
```
6. Install gstreamer dependencies
```
sudo dnf install \
  gstreamer1 \
  gstreamer1-plugins-base \
  gstreamer1-plugins-good \
  gstreamer1-plugins-bad-free \
  gstreamer1-plugins-ugly-free \
  gstreamer1-libav \
  gstreamer1-plugin-openh264
```
7. Install Resonance (I suppose that it's located in the downloads folder and check for the file name, the version can be missmatch)
```
sudo dnf install ./Downloads/Resonance-1.5.1-1.x86_64.rpm -y
```
8. Export the app to the host
```
distrobox-export --app Resonance
```
Done now you can Resonance in you apps !


### Why the Extra Steps?

> [!NOTE]
> **Resonance** is a passion project not signed with an Apple Developer or Windows Store certificate. macOS and Windows will show a security warning as a result. The steps above safely bypass it.
## Q&A

### How do I load music?

- **Drag & drop** or click the **folder icon** and select your music folder.
  - Choose your entire library; full folder trees are supported.
  - Tested on an M1 Pro: a 4-level folder structure with **903 tracks** loads in **~1.16 seconds**.

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/a6a1dfef-c087-436e-89c4-07a22e447951"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/c75d487e-9485-4198-b72f-3a26aa391147" />
  </p>
</div>

### Can I load music from a USB drive, external hard drive, or NAS?

- Yes. Resonance reads from any mounted drive your OS can see: USB sticks, external HDDs, SSDs, you name it.
- If your NAS supports [SMB](https://en.wikipedia.org/wiki/Server_Message_Block), mount the share in your OS and Resonance will read it like any other folder.

### Can I run Resonance from a USB drive alongside my library?

- Yes. Drop the app and your music on the same drive and plug it into any compatible machine. No installation needed.

### The app disappeared. Help?!

> [!NOTE]
> You entered **Mini Mode**. It hides itself when not in use.

- ~~Click~~ hover the **middle-right edge of your screen** (about an inch from the screen border).
- Click the **lock icon** to pin the app in place and prevent this.

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/ebd0ed64-1f45-4d03-ae7c-6221108e5dbc"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/a3b64e3c-8a41-4296-a532-1bcdb1867724" />
  </p>
</div>

### Will there be a mobile or App Store version? What about Chromebook?

- Not planned. Platform rules, fees, and maintenance overhead do not suit a small indie project.
- If there is enough support from the community, we are open to revisiting it.

### Why isn't Resonance open source?

- AI crawlers and vibe-coded clones have made open source challenging for independent developers with limited resources.
- Keeping the codebase closed lets us focus on actually building the thing instead of managing the chaos around it.

## Roadmap

#### Tracklist & Library
- [x] Song title, artist, album art & details
- [x] Bitrate & sample rate
- [x] Codec display
- [x] Multi-folder support
- [x] Drag & drop file support
- [x] Respect CD track order
- [x] Auto-load previous folder on launch
- [x] Search within loaded library

#### Playback
- [x] SFX sounds
- [x] OS media controls *(play, pause, skip via keyboard / system)*
- [ ] Rework of the shuffle (to actually be a list, not a random song that is not the previous song)
- [ ] Gapless playback

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
- [ ] Favorites

#### Interface
- [x] Force light / dark theme
- [ ] Mini Mode left / right position

#### Metadata
- [ ] ID3 tag editor
- [ ] Lyrics support

#### Advanced
- [x] macOS Tahoe Liquid Glass Icon Support
- [ ] Transcoder / remuxer
- [ ] Skin support
- [ ] Play counter
- [ ] Last.fm integration
- [ ] Discord status integration
- [ ] Automatic updates

## Contributing

We value every contribution and carefully read every message, commit, and issue.

- Open an [issue](https://github.com/Oxen-Studio/Resonance/issues) for bugs or feature requests.
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
