# Athana - Lossless Audio Engine

Athana is a stunning, web-based lossless music player that runs entirely in your browser. It features a modern glassmorphism interface, dynamic ambient background effects, and advanced audio processing capabilities. 

Simply load the `Athana_v28.html` file in your browser and sync your local music folder to experience high-fidelity audio playback without any server requirements or backend installations.

## 🌟 Features

* **High-Fidelity Audio:** Native browser support for lossless formats including FLAC, AIFF, WAV, as well as lossy formats like MP3.
* **Immersive Interface:** 
  * Desktop-class glassmorphism design with responsive sidebars.
  * Dynamic, Apple Music-style ambient background blur that reacts to current album art.
  * Animated aurora background effects and customizable interface themes (Focus Mode, reduced animations).
* **Advanced Audio Engine (Sound Lab):**
  * 10-band Equalizer with preamp control.
  * Loudness normalization (ReplayGain style target LUFS).
  * A-B Looping, playback speed control, and track crossfading.
  * Real-time audio spectrum analyzer.
* **Rich Metadata & Visuals:**
  * Automatic ID3 tag and cover art extraction.
  * Interactive, beat-reactive waveform visualization using the HTML5 Canvas API.
  * Detailed audio signal path indicators (codec, bit depth, sample rate, and bitrate).
* **Lyrics Engine:** Support for embedded lyrics, manually loading synced `.lrc` files, Romaji generation for Japanese tracks, and translation capabilities.
* **Local Library Management:** 
  * Securely sync entire local folders or select individual files using the Web Directory API.
  * Persistent library state, queue management, and Liked/Disliked track tagging.

## 🚀 Getting Started

Athana is a purely client-side web application. No build steps, dependencies, or server hosting are required.

1. Download or clone this repository.
2. Open the `Athana_v28.html` file directly in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Click the **+** (Add Media) icon in the top right to select your local music folder or individual audio files.
4. Your library will populate automatically. 

## 🛠️ Technologies Used

* **HTML5 / CSS3 / Vanilla JavaScript:** Core application logic and DOM manipulation.
* **Tailwind CSS:** (via CDN) For rapid, utility-first UI styling.
* **jsmediatags:** (via CDN) For reading audio file metadata and extracting embedded album art.
* **FontAwesome:** (via CDN) For scalable vector icons.
* **Web Audio API:** For real-time audio routing, equalization, and canvas waveform analysis.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
