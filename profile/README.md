<div align="center">
  <img src="https://raw.githubusercontent.com/ppplayermusic/.github/main/profile/banner.jpg" alt="PPPlayer Banner" width="100%" />

  # PPPlayer Music
</div>

---

Hey! Welcome to the PPPlayer organization.

This is the home of **PPPlayer**, a free, open-source music streaming app built with Flutter.

The idea is simple: we wanted an app that feels native and smooth, uses Spotify to explore and discover music, but actually plays the audio via YouTube under the hood. No premium accounts needed, no sign-ups required—just pure music.

### What it does
- **Cross-Platform**: Available natively for macOS, Linux, Windows, iOS, and Android.
- **Exploration**: Powered by Spotify's catalog. Browse featured playlists, new releases, genres, and use full-text search to find exactly what you want.
- **Playback**: Seamlessly resolves tracks and plays them via YouTube. It features a custom hybrid engine supporting robust background processing, lock-screen playback, and hooks right into your device's native media controls.
- **Local Library**: Your history, liked albums, followed artists, and custom playlists are all saved locally on your device (no cloud sync required).
- **The UI**: Built with Material 3 and a sleek dark theme. Includes beautiful adaptive color theming based on album art, interactive vinyl record animations, and a floating video overlay (Picture-in-Picture) to make it feel responsive and alive.

### Under the hood
We like keeping things clean and performant. Here's what we're currently using:
- **App**: [Flutter](https://flutter.dev) (Dart)
- **State Management**: [Riverpod](https://riverpod.dev)
- **Database**: [Drift](https://drift.simonbinder.eu/) (SQLite) & Hive CE for local persistence
- **Playback Engine**: A custom hybrid engine mixing `media_kit` and `youtube_player_iframe`
- **Data Pipeline**: Spotify Web API + our custom YouTube resolver (HTML scraping)

### Repositories
- [**ppplayer**](https://github.com/ppplayermusic/ppplayer) — The main Flutter app. *(Active development!)*
- [**website**](https://github.com/ppplayermusic/website) — The official website and download portal built with Next.js and Tailwind CSS.

### Get involved
We're always tinkering with this. If you want to help out with the UI, improve how we resolve YouTube videos, add translations, or just fix a bug, PRs are super welcome. Feel free to open an issue in the respective repositories if you have an idea or find a bug!

Catch you around!
— Lucas Veneno & the PPPlayer team
