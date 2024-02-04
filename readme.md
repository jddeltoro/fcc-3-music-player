# Music Player

This is a simple music player built with JavaScript. It allows you to play, pause, skip to the next song, go back to the previous song, and shuffle the playlist. You can also delete songs from the playlist.

## Features

- Play/Pause: Click the play button to start playing the current song. If a song is already playing, clicking the play button will pause it.
- Next/Previous: Click the next button to skip to the next song in the playlist. Click the previous button to go back to the previous song.
- Shuffle: Click the shuffle button to randomize the order of the songs in the playlist.
- Delete: Click the delete button next to a song to remove it from the playlist.

## Song Data

The songs are stored in an array of objects, with each object representing a song. Each song object has the following properties:

- `id`: A unique identifier for the song.
- `title`: The title of the song.
- `artist`: The artist of the song.
- `duration`: The duration of the song.
- `src`: The source URL of the song's audio file.

## How to Use

To use the music player, simply open the `index.html` file in your web browser. The playlist will be displayed, and you can use the controls to play, pause, skip, go back, shuffle, and delete songs.

## Future Improvements

- Add a progress bar to show the current playback position in the song.
- Allow the user to add their own songs to the playlist.
- Improve the user interface for a better listening experience.