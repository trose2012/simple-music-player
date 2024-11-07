# Simple Website Music Player

~~Trust me I am good at making titles.~~

This is a simple javascript music player that plays music on your website.

## Features

- Play/Pause
- Skip to next song
- See song title and artist
- See album art
- Add your own music and whatever
- It plays music btw

## How to use

So you need three things to make this work, the HTML snippet, the CSS, JavaScript, and a few SVG files.

1. Copy the HTML snippet into your HTML file.
```html
<!-- Music box start -->
<div id="music-box">
  <img id="music-cover" src="./img/music.png" alt="Cover Art" />
  <p id="music-info"></p>
  <button id="music" class="music" type="audio/mpeg" aria-label="Play/Pause Music"></button>
  <button id="music-skip" class="music" aria-label="Skip current song"></button>
  <audio id="music-src" src="./music/music1.mp3" hidden=""></audio>
</div>
<!-- Music box end -->
```
2. Create a new CSS file and copy the CSS from [music.css](./music.css) into it.
3. Create a new JavaScript file and copy the JavaScript from [music.js](./music.js) into it.
4. Creat a new folder called `svg` and copy the SVG files from [here](./svg) into it.
5. Create a new folder called `music` and copy your music files into it. Name them `music1.mp3`, `music2.mp3`, etc.
6. Create a new folder called `img` and copy your album art into it. Name them `cover1.png`, `cover2.png` etc in the same order as your music files.
7. Update the array in the `music.js` file with the names of your songs.
8. Profit????

## License

Do whatever, I don't care. Just don't claim it as your own and give credit if possible