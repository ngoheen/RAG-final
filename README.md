# RAGBRAI

## Scripts used:

### These scripts came with the template
* <script src="js/jquery-2.1.1.min.js"></script>
* <script src="js/bootstrap.min.js"></script>
* <script src="js/jquery.plugins.js"></script>
* <script src="js/custom.js"></script>

Lots can be removed from the last two scripts

### These scripts all came with lightgallery which is used for popups

* lightgallery.js
* lg-fullscreen.js
* lg-video.js
* lg-zoom.js
* lg-hash.js
<br><br>
* lg.min.js is a minified version of the above scripts
<br><br>
* lg-share-3.js - is for sharing social media on the lightgallery popups and needs work.

### This js is just to make the video play onclick and is way more than needed
All I want is to be able to click *once* on the video that pops up and have it play. Right now, without the following js, I have to click on the video and then on the controls that pop in.
* http://vjs.zencdn.net/5.16.0/video.js
``` 
<script>
    $('.lg-video').on('click', function() {
        $(this).find('video').play();
    });
</script>
```

### This script runs all the carousels
* owl.carousel.min.js


### This script calls lightbox and owlcarousel where needed
* lightbox-script.js