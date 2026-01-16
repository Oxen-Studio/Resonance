<div align="center">
  <img width="128" height="auto" alt="icon" src="/preview/icon.png" />
  <h1>Resonance</h1>
  A lightweight local music player inspired by the golden era of classic desktop players.
  <br>
<br>
<p>
  <img width="49%" height="auto" alt="dark-max" src="/preview/dark-max.png" />
  <img width="49%" height="auto" alt="light-max" src="/preview/light-max.png" />
</p>
</div>

## Why Resonance?

Remember when software had a soul? When your music player didn't need to track you, feed you algorithms, or charge you $120/year just to hear the songs you love?

Resonance brings back that era. No subscriptions, no tracking, no algorithm pushing the latest industry plant. Just you, your music library, and a skeuomorphic interface inspired by the golden age of desktop apps.

All shipped in a basic portable audio player.

**Own your music. Own your experience.**

## Features

Browse your library, play instantly, and enjoy a clean, nostalgic experience.

* **Instant Playback** - Load your albums and play immediately
* **Full Controls** - Play, pause, stop, skip tracks forward and back
* **Shuffle & Loop** - Randomize your library or repeat your favorite song endlessly
* **Volume Control** - Adjust volume or mute as needed
* **Mini Mode** - Compact player that auto-hides when not hovered (lockable if you want it visible)
* **Skeuomorphic Design** - Frutiger Aero aesthetics, because flat design is boring
* **Lightweight** - Won't destroy your RAM or slow you down
* **Zero Tracking** - Your listening habits stay yours
* **100% Local** - No internet required, no data collection, no bullshit

<div align="center">
  <br>
<p>
  <img width="49%" height="auto" alt="dark-mini" src="/preview/dark-mini.png" />
  <img width="49%" height="auto" alt="light-mini" src="/preview/light-mini.png" />
</p>
</div>

## Installation

### For All Platforms

To get started, download the latest version of Resonance for your operating system from the release section.

### Specific Instructions

#### macOS

* Download the `Resonance_mac` file and extract it
* Open the Terminal and navigate to the downloaded folder using `cd`
	+ Example: `cd ./Downloads/Resonance.app`
* Run the command `xattr -dr com.apple.quarantine Resonance.app` to remove quarantine attributes
* You can now launch the app by clicking on the icon or searching for "Resonance" in Spotlight
* Alternatively, you can move the app to your Applications folder using Finder to make it accessible via Launchpad

#### Windows

* Download the `Resonance_win` installer file and extract it
* Double-click on the downloaded file and follow the prompts:
	+ Click "Proceed Anyway" when prompted by Windows Defender
	+ Confirm the installation settings (or change them if desired)
	+ Click "OK" to complete the installation
* Once installed, you can launch the app from the Start menu or desktop icon

#### Linux

TBA

### Why the Extra Steps?

Resonance is a passion project, and as such, we don't have the budget for Apple Developer or Windows Store fees. As a result, the app is not signed with 
their respective digital certificates, which triggers security warnings on both macOS and Windows. By following these steps, you can safely bypass these 
warnings and enjoy using Resonance!

## How to use?

### How to load musics?

* Click on the folder icon and select the folder containing your music files.
* Note: Currently, Resonance only supports loading one folder at a time. We're working on improving this feature!

### How to minify the app?

* Click on the button above the volume control to minimize Resonance.

### The app has disappeared, help !?

* Click in the middle-right section of the screen (10px from the screen border). This will reopen the app.

### I want to prevent the app from disappearing

* Click on the lock icon. This will "pin" the app to its current state, preventing it from disappearing.

## Bonus !

We made a little bash script to help you manage your music, it's not much, but it's honest work [oxen-converter](https://github.com/Oxen-Studio/oxen-converter)

## Roadmap

1. **Tracklist Window Enhancements**
	* Develop a detailed track list window displaying metadata such as:
		- Song title and artist
		- Album art and details
		- Bitrate, sample rate, and codec information for each file
2. **Folder Handling**
	* Support multiple folder selection and management (Yes we only handle one folder, but we have to start somewhere aren't we?)
3. **Equalizer Window**
	* Implement an intuitive equalizer for customizing audio settings
4. **ID3 Tag Updater Window**
	* Update metadata with accurate information
5. **Transcoder/Remuxer Window**
	* Allow seamless transcoding and remuxing of audio files
6. **Library maker window**
	* Update your library folder to create, based on the metadata, the artist/album folders containing your music files.

## Contributing

Found a bug? We'll send you a picture of a thumbs-up in exchange for any identified bug.

* Open an issue for bugs or feature requests  
* ~~Share feedback on Twitter/X or in the comments~~ (Not yet created, but we will be very happy to see you share your love for it)
* Have an idea for a custom skin? Let us know

## Philosophy

Technology used to be cool. Your music player didn't spy on you. The internet wasn't five websites in a trench coat.

Resonance isn't trying to kill Spotify. We're just giving you back what you lost: a simple tool that does one thing well, respects you, and doesn't treat your music library like a data mine.

Stop renting. Start owning.

## Technologies

Powered by [React](https://react.dev/) and [Tauri](https://v2.tauri.app/).

---

###### © 2026 Oxen Studio
