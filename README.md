</p>
<h1 align="center">Omicron</h1>
<p align="center">

</p>

Modern Android Media Downloader powered by `yt-dlp` & `gallery-dl`

<div align="center">
  <img src="https://github.com/hamzabellouch/omicron/blob/68cf29c17e1849e20f02d4f7871923bac25cf842/Images/Omicron.png" alt="Omicron" width="800"/>
</div>

### <a name="About"></a> 📖 About

**Omicron** is a powerful, user-friendly, and beautifully designed media downloader for Android.  
Powered by `yt-dlp` and `gallery-dl`, it allows users to download videos, audio files, and entire playlists from hundreds of supported platforms while offering complete control over subtitles, metadata, and custom commands.

Omicron is built using modern Android technologies and follows the principles of **Modern Android Development (MAD)** to ensure performance, stability, and a clean user experience.

The application focuses on simplicity, speed, and flexibility, making it suitable for both casual users and advanced users who need full control over media downloading workflows.

### <a name="Screenshots"></a> 📸 Screenshots

Omicron UI & Features :

<div align="center">
<div>
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Home.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Downloads.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Profile.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Settings.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/General.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Download%20directory.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Format.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Network.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Custom%20command.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Look%20%26%20feel.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Interface%20%26%20interaction.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Running%20tasks.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/Auto%20update.jpg" width="30%" />
<img src="https://github.com/hamzabellouch/omicron/blob/main/Images/About.jpg" width="30%" />
</div>
</div>

<br>

### <a name="Features"></a> ⭐ Features - Supported +1000 platform

Examples of popular platforms :

| Platform | Engine Used | Video Support | Audio Extraction | Image Support | Metadata Processing Speed | Download Speed |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **YouTube** | `yt-dlp` | Full (up to 8K, HDR, 60fps) | Full (Extracted & encoded via FFmpeg) | Thumbnail extraction only | **Slow** (~60s) | **Throttled / High-Speed** (Bypassed by yt-dlp; accelerated via `aria2c`) |
| **Instagram** | `yt-dlp` & `gallery-dl` | Full (Reels, Stories, IGTV, Posts) | Supported (from video posts/reels) | Full (Carousels, posts, profile pics via gallery-dl) | **Moderate** (~20s) due to Meta rate-limiting | **High-Speed** (Strict IP rate-limiting applied by Meta) |
| **Facebook** | `yt-dlp` | Full (Watch, Reels, Page videos) | Supported | N/A | **Moderate** (~20s) | **Moderate to High-Speed** |
| **TikTok** | `yt-dlp` | Full (Watermark removal option) | Supported | Full (Photo-slideshow posts) | **Fast** (~10s) | **Very High-Speed** (Uses edge CDNs) |
| **X (Twitter)** | `yt-dlp` & `gallery-dl` | Full (All public video posts) | Supported | Full (Attached images via gallery-dl) | **Moderate** (~20s) | **High-Speed** |
| **Reddit** | `yt-dlp` & `gallery-dl` | Full (Muxed audio/video via FFmpeg) | Supported | Full (Image galleries, single images) | **Moderate** (~20s) | **High-Speed** |

### <a name="TechStack"></a> 🛠 Tech Stack & Architecture

Omicron follows modern Android architecture principles for better maintainability and performance.

* `100% Kotlin & Coroutines / Flow`
* `Jetpack Compose`
* `Single Activity Architecture`
* `Material Design 3` & `Dynamic Colors` (Material You)
* `Koin` (Dependency Injection)
* `Room Database` (Local Storage)
* `MMKV` (Fast Key-Value Storage)
* Core Engines:
  - `yt-dlp` (Video/Audio Downloader)
  - `gallery-dl` (Image/Gallery Downloader)
  - `aria2c` (Multi-connection download accelerator)
  - `FFmpeg` (Post-processing & muxing)
* `Coil` (Image Loading)

### <a name="Installation"></a> 🔥 Installation

1. Go to the Releases page:
   https://github.com/hamzabellouch/omicron/releases

2. Download the latest `.apk` file.

3. Install the application on your Android device.

4. Make sure that: `Install from unknown sources` is enabled in your Android settings.

### <a name="Build"></a> 🔨 Building from Source - Not available yet


>To build Omicron locally, make sure you have the latest version of Android Studio installed.
>1. Clone the repository: `git clone https://github.com/hamzabellouch/omicron.git`
>2. Open the project in Android Studio.
>3. Sync Gradle dependencies.
>4. Build and run the application on your device or emulator.


> [!WARNING]
> There is always a possibility of error, so we assume no responsibility for any inaccuracies.


### <a name="Copyright©2026"></a> Copyright © 2026

Thank you for checking out Omicron. If you have any feedback or suggestions, feel free to contact us:
hamzabellouchcontact@gmail.com

Stay connected and follow us on:  
[Facebook](https://facebook.com/hamzabellouch1) | [Instagram](https://instagram.com/hamzabellouch0) | [Twitter](https://twitter.com/hamzabellouch0) | [Telegram](https://t.me/hammzabellouch) | [LinkedIn](https://www.linkedin.com/in/hamzabellouch)
