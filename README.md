# Cryptoplace

A clone of /r/place backed by the blockchain.

I was really curious about using the blockchain as a database. I guess I found a way.

The grid is a 100 by 100 (might expand, depends on how the experiment goes).
Each pixel has 16 corresponding bitcoin addresses, one for each color.
The address with the most bitcoin received, decides the color.

I really wanted to populate the grid by using actual bitcoin but it would be too expensive
for me to do it. Sorry. Instead, I chose some nice default images. Hope you override them.

A pixel is colored only once the transaction is confirmed.

# Thanks

https://github.com/waynegm/imgViewer2

https://github.com/Leaflet/Leaflet
