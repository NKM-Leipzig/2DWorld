---
title: "Das Naturkundemuseum Leipzig präsentiert"
layout: archive
classes: wide
---
<div class="yt">
  <iframe id="ytframe" width="560" height="315" src="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<script>
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

    let ytframe = document.getElementById("ytframe");
    let adsURL = "https://www.youtube-nocookie.com/embed/"+urlParams["ytvideoid"];
    console.log(adsURL);
    ytframe.src = adsURL;
</script>
