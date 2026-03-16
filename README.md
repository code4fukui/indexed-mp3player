# indexed-mp3player

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple indexed MP3 player that allows users to upload and play MP3 files using the IndexedDB and IndexedStorage APIs.

## Features
- Drag and drop MP3 files to upload them to the application
- Play, stop, and clear the playlist
- Stores MP3 files in IndexedDB for persistent storage
- Automatically plays the next song in the playlist when the current one finishes

## Requirements
This application requires a modern web browser that supports the IndexedDB and IndexedStorage APIs.

## Usage
1. Open the `index.html` file in a web browser.
2. Drag and drop MP3 files into the designated area to add them to the playlist.
3. Click the "PLAY" button to start playing the first song in the playlist.
4. Click the "STOP" button to pause the current song.
5. Click the "CLEAR" button to remove all songs from the playlist.

## Libraries
This application uses the following open-source libraries:
- [IndexedDB](https://github.com/code4fukui/IndexedDB)
- [IndexedStorage](https://github.com/code4fukui/IndexedStorage)

## License
MIT License — see [LICENSE](LICENSE).