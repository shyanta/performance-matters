# Audit

## Images
* The images used on the homepage are ~200kb each. This can be much better. The loading time right now is 41.97 seconds.
By downsizing the images, you can speed up this process a lot.
![Page Load without Changes](screenshots/img-before.jpg)
With the downsized images the pages has a loading time of 29.97 seconds.
![Page Load with Changes](screenshots/img-after.jpg)
* Also, these images are about 800px - 600px, while they are used in a much smaller context. I scaled them down to 500px - 375px.
This move reduced the loading speed to 25.43 seconds.
![Page Load with small images](screenshots/img-small.jpg)
* To downsize the Images even more, I converted them from jpg to webp. This reduced the page load to 23.07 seconds and I placed the images in a picture element.
![Page Load with webp](screenshots/img-webp.jpg)
