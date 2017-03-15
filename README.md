# RAGBRAI

## Scripts used:


###These scripts came with the template
<script src="js/jquery-2.1.1.min.js"></script>
<script src="js/bootstrap.min.js"></script>

Lots can be removed from the two following scripts
<script src="js/jquery.plugins.js"></script>
<script src="js/custom.js"></script>




<script src="js/lg.min.js"></script>
<!-- above is the minified version of all the scripts below, in one script -->

<!-- these scripts all came with lightgallery which is used for popups -->
<!--
<script src="lightGallery-master/demo/js/lightgallery.js"></script>
<script src="lightGallery-master/demo/js/lg-fullscreen.js"></script>
<script src="lightGallery-master/demo/js/lg-video.js"></script>
<script src="lightGallery-master/demo/js/lg-zoom.js"></script>
<script src="lightGallery-master/demo/js/lg-hash.js"></script>
-->
<script src="js/lg-share-3.js"></script><!-- this needs to properly add the social media links -->
<!-- /.lightgallery -->

<!-- this js is just to make the video play onclick and is way more than needed -->
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