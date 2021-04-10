---
title: "Das Naturkundemuseum Leipzig präsentiert"
layout: archive
classes: wide
---
<div class="yt">
  <video id="theplayer" autoplay="autoplay" height="360px" controls="controls">
    <source id="mediasource" type="video/mp4">
      <p>Schade!</p>
      Dein Browser unterstützt leider keine Videovidergabe.
  </video>
  <p>Das funktioniert am besten mit Chromium/Chrome. Du kannst hier ein Video erwarten.</p>
</div>
<script>
    var player = document.getElementById("theplayer");
    var urlParams;
    (window.onpopstate = function () {
        var match,
            pl     = /\+/g,  // Regex for replacing addition symbol with a space
            search = /([^&=]+)=?([^&]*)/g,
            decode = function (s) { return decodeURIComponent(s.replace(pl, " ")); },
            query  = window.location.search.substring(1);

        urlParams = {};
        while (match = search.exec(query))
        urlParams[decode(match[1])] = decode(match[2]);
    })();
    player.src = "https://world.naturkunde.museum/movies/"+urlParams["media"];
    player.focus();
    player.onloadeddata = function() {
        player.play();
    };
    document.getElementById("mediasource").play();
    player.load();
</script>
