# Kinema — Movie & TV Show App for Windows with Torrent Streaming and Built-in Player

**Kinema** is a free movie and TV show app for Windows 10 and Windows 11. Browse a catalog of films, series, anime and cartoons, watch trailers, stream torrents without waiting for the download to finish, and play everything in a fast VLC-based player with HDR, motion smoothing and casting to your TV.

[![Download for Windows](https://img.shields.io/badge/Download-Kinema.exe-orange?style=for-the-badge&logo=windows)](https://github.com/kinema-app/kinema/releases/latest/download/Kinema.exe)
[![Latest release](https://img.shields.io/github/v/release/kinema-app/kinema?style=for-the-badge)](https://github.com/kinema-app/kinema/releases/latest)

One portable `.exe`, no installer, no account, no ads. Kinema updates itself automatically.

## Features

### Movie and TV catalog
- Trending, popular and new movies and TV shows, anime and cartoons on a Microsoft Store–style home page
- Filters by genre, country, year and rating, plus ready-made collections
- Instant search with suggestions for movies, series and people
- Movie and series pages with trailers, ratings, cast and crew, seasons and episodes, and similar titles
- Actor and director pages with biography and full filmography
- Favorites, watch history and **Continue watching** that resume exactly where you stopped
- Catalog in about 80 languages; interface in English, Russian, Ukrainian, German, French and Spanish

### Torrent streaming
- Search torrents for any movie or episode right from its page
- Start watching a torrent immediately with the built-in streaming engine (TorrServer)
- Picks the right file and episode in multi-file releases and shows quality, size and seeders

### Video player
- Plays almost any format: MKV, MP4, AVI, HEVC, AV1, 4K and HDR10
- **Automatic HDR**: turns on Windows HDR for HDR videos and turns it off afterwards
- **Smooth motion ×2**: frame interpolation (MEMC) that turns 24 fps into 48 fps, powered by VapourSynth and MVTools
- Removes black bars from letterboxed movies and lets you move the picture away from subtitles
- Night mode (volume normalization), so you can hear quiet dialogue without loud explosions
- Picture-in-picture, auto-play of the next episode, resume playback, customizable subtitles
- Keyboard shortcuts: Space, ←/→, J/L, F, M, P, N, I and more

### Cast to TV
- Stream to **Chromecast**, Android TV and Google TV
- Stream to **DLNA** smart TVs: Samsung, LG, Sony, Philips and others

### Offline downloads
- Download movies and episodes and watch them without internet, in the same player

### Works on any network
- Built-in proxy support (HTTP and SOCKS5), DNS-over-HTTPS and an IPv4-only mode
- Switches automatically to a working mirror when the catalog is unreachable

## Download and install

1. Download **[Kinema.exe](https://github.com/kinema-app/kinema/releases/latest/download/Kinema.exe)** from the latest release.
2. Run it. No installation is needed.

If Windows SmartScreen shows "Windows protected your PC", click **More info** → **Run anyway**. The app is not code-signed yet.

**Requirements:** Windows 10 version 2004 or later, or Windows 11, 64-bit (x64). The first launch can take up to 30 seconds while Windows checks the files; later launches are instant.

## FAQ

**Is Kinema free?**
Yes. Kinema is free to download and use.

**Do I need to create an account?**
No. There is no sign-up and no login.

**How do I update Kinema?**
You don't need to. Kinema checks for a new version at startup, downloads it in the background and restarts when you are not watching anything.

**Where is my data stored?**
Settings, favorites, history and downloads stay on your PC in `%LOCALAPPDATA%\Kinema`.

## Disclaimer

Kinema does not host, upload or distribute any video content. It shows publicly available metadata and plays media from sources that you choose. You are responsible for complying with the copyright laws of your country.

Movie and TV metadata and images are provided by [The Movie Database (TMDB)](https://www.themoviedb.org/). This product uses the TMDB API but is not endorsed or certified by TMDB.

Kinema is built with WinUI 3, .NET, LibVLC, TorrServer, VapourSynth and other open-source components. Their licenses are listed in the app under **Settings → About → Third-party components**.
