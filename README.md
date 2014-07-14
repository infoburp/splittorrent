splittorrent
============

bittorrent client in the web browser

server (written in c) - provides a websocket connection to the client, allowing the browser to make arbitrary connections, and supplies the client html/js/css to the client browser.

client (html5/js/css) - downloads torrent until sufficient buffer, then plays <video> or <audio> in tags.
