# SimpleMusicPlayer for Rainmeter

A clean Rainmeter music player skin designed for YouTube Music through
WebNowPlaying. It includes horizontal and vertical layouts, playback controls,
album art, progress display, and an audio visualizer.

<img width="1088" height="648" alt="SimpleMusicPlayer preview" src="https://github.com/user-attachments/assets/fe034306-fcc1-40aa-b119-f32533fa12f5" />

## Features

- Dynamic audio visualizer with improved peak response
- Horizontal and vertical layout modes
- Play, pause, next, previous, repeat, and shuffle controls
- Real-time title, artist, album art, and progress bar
- Quick access rating buttons
- Bundled NanumGothic font resource

## Requirements

- [Rainmeter](https://www.rainmeter.net/)
- YouTube Music in a Chromium-based browser
- [WebNowPlaying Companion](https://chromewebstore.google.com/detail/webnowplaying/jfakgfcdgpghbbefmdfjkbdlibjgnbli)

This skin is optimized for the YouTube Music web player. Desktop players such as
Spotify or iTunes are not the target environment.

## Installation

1. Install Rainmeter.
2. Install the WebNowPlaying Companion browser extension.
3. Download and install the SimpleMusicPlayer Rainmeter skin package.
4. Open YouTube Music in your browser.
5. Load either `SimpleMusicPlayer.ini` or `Vertical.ini` from Rainmeter.

## Layouts

| File | Purpose |
| --- | --- |
| `SimpleMusicPlayer/SimpleMusicPlayer.ini` | Horizontal player layout |
| `SimpleMusicPlayer/Vertical.ini` | Vertical player layout |
| `SimpleMusicPlayer/@Resources` | Fonts and shared resources |

## Notes

- Browser-to-widget sync can depend on the current WebNowPlaying browser state.
- Repeat and shuffle are beta features.
- Previous-track behavior can be limited by the browser player's current queue
  state.

## Release History

| Version | Changes |
| --- | --- |
| `v3.0` | Added vertical mode layout |
| `v2.0` | Added background options and rating buttons; fixed general issues |
| `v1.2.1` | Improved font sizing, styles, visualizer sensitivity, and height |
| `v1.2` | Added integrated audio visualizer and redesigned player information |
| `v1.1` | Added repeat and shuffle beta controls; fixed next button behavior |

## Download

- [DeviantArt release page](https://www.deviantart.com/yujio03/art/SimpleMusicPlayer-3-0-1-1109940258)
