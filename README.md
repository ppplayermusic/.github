<div align="center">
  <img src="https://raw.githubusercontent.com/ppplayermusic/.github/main/profile/banner.png" alt="PPPlayer Banner" width="100%" />

  # PPPlayer Music
</div>

---

Hey! Welcome to the PPPlayer org.

This is the home of **PPPlayer**, a music app we're building with Flutter. 

The idea is simple: we wanted an app that feels native and smooth, uses Spotify to explore and discover music, but actually plays the audio via YouTube under the hood. No premium accounts needed, just music.

### What it does
- **Exploration**: Uses Spotify's catalog so you can browse playlists, new releases, and search for exactly what you want.
- **Playback**: Takes those tracks and plays them via YouTube. It runs entirely in the background and hooks right into your phone's native media controls.
- **Local Library**: Your history, liked albums, followed artists, and custom playlists are all saved locally on your device (no cloud sync required). 
- **The UI**: Built with Material 3, a dark theme, and some neat animations (like floating video overlays) to make it feel responsive and alive.

### Under the hood
We like keeping things clean and performant. Here's what we're currently using:
- **App**: [Flutter](https://flutter.dev)
- **State Management**: [Riverpod](https://riverpod.dev)
- **Database**: [Drift](https://drift.simonbinder.eu/) (SQLite) & Hive
- **Playback Engine**: A custom engine mixing `media_kit` and `youtube_player_iframe`
- **Data**: Spotify Web API + our own YouTube resolver

### Repositories
- [**ppplayer**](https://github.com/ppplayermusic/ppplayer) — The main Flutter app. *(Active development!)*

### Get involved
We're always tinkering with this. If you want to help out with the UI, improve how we resolve YouTube videos, or just fix a bug, PRs are super welcome. Feel free to open an issue if you have an idea.

Catch you around!
— Lucas Veneno & the PPPlayer team
