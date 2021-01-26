---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

This website contains a map for [Workadventu.re](https://workadventu.re).

You can access this map at <a id="mapLink" href=""></a>

<script>
    window.onload = function() {
        var path = window.location.pathname;
        if (path.endsWith('index.html')) {
            path = path.substr(path, path.length - 'index.html'.length);
        }
        var url = 'https://play.workadventu.re/_/global/'+window.location.host+path+'map.json';
        document.getElementById('mapLink').href = url;
        document.getElementById('mapLink').innerText = url;
    };
</script>
