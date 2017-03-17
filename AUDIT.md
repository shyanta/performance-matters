# Audit

<<<<<<< HEAD
## CSS
* Adding the bootstrap CDN for the bootstrap CSS File. Before the CDN, the page load was 45.91 seconds.
![Page Load without Changes](screenshots/start.jpg)
After adding the CDN, the loading time was reduced to 36.21 seconds.
![Page Load with CDN](screenshots/cdn.jpg)
* I minified the CSS File, this reduced the loading speed to 32.88 seconds.
![Page Load with Minified CSS](screenshots/minified.jpg)
* I added a critical CSS and used LoadCSS to load the rest of the CSS'es later on.
This reduced the loading speed to 33.09 seconds.
![Page Load with Critical and LoadCSS CSS](screenshots/critical.jpg)
=======
## JS
* Adding the bootstrap CDN for the bootstrap JS File. Before the CDN, the page load was 42.71 seconds.
![Page Load without Changes](screenshots/start.jpg)
After adding the CDN, the loading time was reduced to 40.70 seconds.
![Page Load with CDN](screenshots/cdn.jpg)
* I added Compression to the page. On each request it will compress the files. This reduced the page load to 32.05 seconds.
![Page Load with Compressor](screenshots/compressed.jpg)
>>>>>>> OptimizeJS
