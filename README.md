# indexed-mp3player

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, browser-based MP3 player that uses the IndexedDB API to store your music library locally, allowing for persistent playback across sessions.

## Features

-   **Drag & Drop Upload:** Add MP3 files to your library by dragging them directly into the browser window.
-   **Persistent Storage:** Leverages IndexedDB to store audio files, so your playlist persists even after closing the browser tab.
-   **Playback Controls:** Standard controls to play, stop, and clear the entire playlist.
-   **Direct Track Selection:** Click any track in the list to play it immediately.
-   **Continuous Play:** Automatically plays the next song in the list when the current one finishes.
-   **Session Resume:** Remembers and highlights the last played track when you reopen the application.

## Usage

1.  Open the `index.html` file in a modern web browser.
2.  Drag and drop your MP3 files onto the main content area. They will be saved to the browser's database and appear in the playlist.
3.  Click any track name to begin playback.
4.  Use the `PLAY` button to start or resume from the currently selected track.
5.  Use the `STOP` button to pause playback.
6.  Use the `CLEAR` button to permanently delete all tracks from storage.

## Libraries Used

This application is built with the following open-source libraries:

-   [IndexedDB](https://github.com/code4fukui/IndexedDB): A promise-based wrapper for the IndexedDB API.
-   [IndexedStorage](https://github.com/code4fukui/IndexedStorage): A simple key-value store wrapper for IndexedDB.
-   [dataencoder](https://github.com/code4fukui/dataencoder): A utility for encoding binary data into data URLs.

## License

MIT License - see [LICENSE](LICENSE).