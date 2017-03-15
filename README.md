# RAGBRAI

## Scripts used:

### These scripts came with the template
* <script src="js/jquery-2.1.1.min.js"></script>
* <script src="js/bootstrap.min.js"></script>
* <script src="js/jquery.plugins.js"></script>
* <script src="js/custom.js"></script>

Lots can be removed from the last two scripts





<script src="js/lg.min.js"></script>
### above is the minified version of all the scripts below, in one script

### These scripts all came with lightgallery which is used for popups

* lightgallery.js
* lg-fullscreen.js
* lg-video.js
* lg-zoom.js
* lg-hash.js

* lg.min.js is a minified version of the above scripts

* lg-share-3.js - is for sharing social media and needs work.

### This js is just to make the video play onclick and is way more than needed
<script src="http://vjs.zencdn.net/5.16.0/video.js"></script>
<script>
$('.lg-video').on('click', function() {
        $(this).find('video').play();
    });
</script>

<!-- this script runs all the carousels -->
<script src="js/owl.carousel.min.js"></script>
<!-- /.carousels -->

<!-- this script calls lightbox and owlcarousel where needed-->
<script src="js/lightbox-script.js"></script>