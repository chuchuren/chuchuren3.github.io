---
layout: page
title: Music
permalink: /music/
---

{% raw %}
<iframe id="music-player" src="" frameborder="0" allowfullscreen></iframe>

<script>
  function getRandomMusic() {
    var musicList = [
      'https://github.com/chuchuren/chuchuren3.github.io/blob/master/assets/music/01.mp3',
      'https://github.com/chuchuren/chuchuren3.github.io/blob/master/assets/music/02.mp3',
      'https://github.com/chuchuren/chuchuren3.github.io/blob/master/assets/music/03.mp3'
    ];
    var randomIndex = Math.floor(Math.random() * musicList.length);
    var musicUrl = musicList[randomIndex];

    var musicPlayer = document.getElementById('music-player');
    music
