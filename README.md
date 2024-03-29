![](https://raw.githubusercontent.com/dieb/spotify-lyrics/master/assets/img/logo.png)

Lyrics companion desktop app for Spotify.


## Usage

[Download the latest release!](https://github.com/dieb/spotify-lyrics/releases)

If you're on macOS, you can also build it and run it by running these commands:

```bash
$ npm install && npm start
```

## Screenshots

Click to view.

[![screenshot1](https://raw.githubusercontent.com/dieb/spotify-lyrics/master/assets/img/screenshot1-th.png)](https://raw.githubusercontent.com/dieb/spotify-lyrics/master/assets/img/screenshot1.png)
[![screenshot2](https://raw.githubusercontent.com/dieb/spotify-lyrics/master/assets/img/screenshot2-th.png)](https://raw.githubusercontent.com/dieb/spotify-lyrics/master/assets/img/screenshot2.png)

## Building package

```bash
$ make build
```


## License

This project is merely an experiment for educational purposes. It's sole intent is to explore building desktop apps with Electron and make use of Spotify's AppleScript API and dbus messages. This project's code is in the public domain.

Use it at your own risk. This project does not endorse nor support any inappropriate use of lyrics as they are subject to copyright law. Lyrics are provided by ChartLyrics.com whose license is free for non-commercial use.


## TODO

- Implement Menu / About
- Implement dbus monitor for Linux build (`spotify_local_control`)
- Test build on Linux
- Research a way to get the current playing track on Windows
- Refactor `searchLyrics`
- Research other providers
