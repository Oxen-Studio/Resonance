<div align="center">
  <h6>macOS → Read the <a href="#installation">installation</a> guide or the app won't launch.</h6>
  <br>
  <img width="96" height="auto" alt="icon" src="https://github.com/user-attachments/assets/5fbce515-9399-457e-9879-835ad3597fac" />
  <h1>Resonance</h1>
  A lightweight local music player inspired by the golden era of classic desktop players.
  <br><br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/c1617d50-0807-4ea4-98da-9789e2b0fc16" />
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/6fa27488-6768-400f-9105-ce64ba52faaa" />
  </p>
</div>

## Why Resonance?

Remember when software had a soul?  
When your music player didn’t track you, feed you algorithms, or charge you $120/year just to hear the songs you already own?

[Resonance](https://github.com/Oxen-Studio/Resonance) brings back that era.  
No subscriptions. No tracking. No algorithm pushing the latest industry plant.  
Just you, your music library, and a skeuomorphic interface inspired by the golden age of desktop apps.

All shipped as a simple, portable audio player.

**Own your music. Own your experience.**

## Features

Browse your library, hit play instantly, and enjoy a clean, nostalgic experience.

- **Instant Playback** - Load albums and play immediately
- **Full Controls** - Play, pause, stop, next, previous
- **Shuffle & Loop** - Randomize your library or loop a single track
- **Volume Control** - Adjust volume or mute anytime
- **Equalizer** - Tune frequencies to your taste
- **Mini Mode** - Compact player that auto-hides when not hovered (lockable)
- **Skeuomorphic Design** - Frutiger Aero vibes, because flat design is boring
- **Lightweight** - Won’t eat your RAM or slow you down
- **Zero Tracking** - Your listening habits stay yours
- **100% Local** - No internet, no data collection, no bullshit

<div align="center">
  <br>
  <p>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/4c20e612-9501-48bc-b418-0b4f4def8185"/>
    <img width="49%" height="auto" alt="" src="https://github.com/user-attachments/assets/898fe7fb-d9ff-4d9f-bc7b-b44dbd484b4f" />
  </p>
</div>

## Installation

Download the [latest version](https://github.com/Oxen-Studio/Resonance/releases) for your operating system and carefully follow the instructions below.

### macOS

###### Apple Silicon
(macOS Sonoma/Sequoia/Tahoe, others like Monterey should works but no tested)
- Download `Resonance_mac` and extract it.

> [!IMPORTANT]
> 1. Open **Terminal** and navigate to the folder where the app is located  
>    e.g. `cd Downloads`  
> 2. Remove quarantine attributes using the following command:  
>    `xattr -dr com.apple.quarantine Resonance.app`

- You can now safely use [Resonance](https://github.com/Oxen-Studio/Resonance)
  - Launch it instantly from anywhere by simply double-clicking it.
  - Or move the app to your `Applications` folder for quick access via **Spotlight**.

### Windows
(Windows 10/11, Windows 8 untested)
- Download `Resonance_win` installer and extract it.
- Double-click the installer and follow the prompts:
  - Click `Proceed Anyway` if **Windows Defender** warns you.
  - Confirm (or change) installation settings.
  - Click `OK` to finish.
- Launch from **Start Menu** or desktop shortcut.

### Linux

**TBA**

### Why the Extra Steps?

> [!NOTE]
> [Resonance](https://github.com/Oxen-Studio/Resonance) is a passion project. We don’t pay for Apple Developer or Windows Store certificates.

Because the app isn’t digitally signed, macOS and Windows will show security warnings.  
Following the steps above safely bypasses those warnings so you can use Resonance normally.

## Q&A

<details open>
<summary><h3>How do I load music?</h3></summary>

- Click the <b>folder icon</b> and select your music folder.
  - Choose your entire library; full folder trees are supported
  - Tested on an M1 Pro: a 4-level folder structure with <b>903 tracks</b> loads in <b>~1.16 seconds</b>

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

## Roadmap (Unordered)

- [ ] **Tracklist Window Enhancements**
  - [x] Song title & artist
  - [x] Album art & album details
  - [x] Bitrate, sample rate
  - [ ] Codec
- [x] **Folder Handling**
  - [x] Multiple folder support
- [x] **Equalizer Window**
  - [x] Basic EQ controls
- [ ] **ID3 Tag Updater**
- [ ] **Transcoder / Remuxer**
- [ ] **Library Maker**
- [ ] **Visualizer**
  - [x] Simple visualizer
  - [ ] Old-school visualizer
- [ ] **Equalizer Upgrade**
  - [x] Presets
  - [x] Left/right balance
  - [ ] Pitch & speed
- [ ] **Play Counter**
- [ ] **Skin Handler**
- [x] **Sfx Sounds**

### Bonus

> [!NOTE]
> We made a small bash script to help manage your music. It’s not much, but it’s honest work.  
> [Oxen Converter](https://github.com/Oxen-Studio/oxen-converter)

## Contributing

> [!TIP]
> Found a bug?  
> We value every contribution and carefully read every message, commit, and issue. We’ll definitely reply to each one.

- Open an issue for bugs or feature requests.
- Share feedback on [Reddit](https://reddit.com/r/ResonanceApp/).
- Got an idea for a custom skin? Let us know.

## Philosophy

Technology used to be cool.  
Your music player didn’t spy on you.  
The internet wasn’t five websites in a trench coat.

Resonance isn’t trying to kill Spotify.  
It’s just giving you back what you lost.

**Stop renting. Start owning.**

---

Powered by [React](https://react.dev) and [Tauri](https://v2.tauri.app/).

###### © 2026 Oxen Studio
