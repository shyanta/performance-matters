# Audit

## JS
* Adding the bootstrap CDN for the bootstrap JS File. Before the CDN, the page load was 42.71 seconds.
![Page Load without Changes](screenshots/start.jpg)
After adding the CDN, the loading time was reduced to 40.70 seconds.
![Page Load with CDN](screenshots/cdn.jpg)
* I added Compression to the page. On each request it will compress the files. This reduced the page load to 32.05 seconds.
![Page Load with Compressor](screenshots/compressed.jpg)