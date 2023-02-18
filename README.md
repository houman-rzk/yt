# yt

A script for managing YouTube channel and playlist subscriptions and watching videos.


## About
Since ordering by uploads by date became impossible in youtube.com and most of its frontends, I often found myself scrolling for an absurd amount of time wanting to watch a recently-discovered-channel's oldest videos.

This script was created to satisfy that simple need: easily retrieving and entire channel's videos.

It also deals with the ad and bloat issues of youtube.com.

This script uses a local database to store all the video ids from synced YouTube channels and playlists. To sync a channel/playlist means to retrieve and store all it's ids. Syncing takes only a few seconds.

This script also allows the user to search a video and play it.


## Dependencies
- mpv
- yt-dlp
- dmenu
- sqlite3
- (optional) umpv.py for queuing


## Installation
Copy `yt` to your PATH and make it executable.


## Usage
`yt`
