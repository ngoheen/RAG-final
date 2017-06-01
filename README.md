# RAGBRAI

### Links to flat pages:

| Page Links    |                                                                                                      |
| ------------- | ---------------------------------------------------------------------------------------------------- |
|__Homepage__   |[index page](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/ragbrai-home.html)                   |
| __Shop__      |[section front](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-shop.html)           |
|               |[product page](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/shop-product.html)                 |
|               |[cart](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/shop-cart.html)                            |
|               |[checkout](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/shop-checkout.html)                    |
|               |[payment](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/shop-checkout2.html)                    |
|               |[confirmation](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/shop-confirmation.html)            |
|__Galleries__  |[photo gallery](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-photogallery.html)   |
|               |[video gallery](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-video.html)          |
|               |[podcasts](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-podcast.html)             |
|__Blog__       |[blog front](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-blog.html)              |
|               |[blog post](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/blog-post.html)                       |
|__User__       |[create account](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/user-create-account.html)        |
|               |[user profile](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/user-profile.html)                 |
|               |[user group](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/user-group.html)                     |
|               |[user group index](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/user-group-index.html)         |
|__The Ride__   |[The Ride](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/the-ride.html)                         |
|__Register__   |[Registration](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/registration.html)                 |
|__Forums__     |[forums index](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/sectionfront-forums.html)          |
|               |[forums post](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/forums-post.html)                   |
|               |[forums index with create topic](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/index-forum.html)|
|__Search__     |[search results](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/search-result.html)              |
|__Errors__     |[404 page](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/404.html)                              |
|               |[505 page](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/505.html)                              |
|__Contact__    |[contact page](http://www.gannett-cdn.com/LDSN/desmoines/RAG-final/contact.html)                      |
<br>

### Scripts used:

#### These scripts came with the template
* jquery-2.1.1.min.js
* bootstrap.min.js
* jquery.plugins.js - this is all the plugins they used, in one script
* custom.js

Lots can be removed from the last two scripts, above.

#### These scripts all came with lightgallery which is used for popups

* lightgallery.js
* lg-fullscreen.js
* lg-video.js
* lg-zoom.js
* lg-hash.js
<br><br>
* lg.min.js is a __minified version__ of the above scripts
<br><br>
* lg-share-3.js - is for sharing social media on the lightgallery popups and needs work.

#### This js is just to make the video play onclick and is way more than needed
All I want is to be able to click **once** on the video that pops up and have it play. Right now, without the following js, I have to click on the video and then on the controls that pop in.
* http://vjs.zencdn.net/5.16.0/video.js
``` 
<script>
    $('.lg-video').on('click', function() {
        $(this).find('video').play();
    });
</script>
```

#### This script runs all the carousels
* owl.carousel.min.js


#### This script calls lightgallery and owlcarousel where needed
* lightbox-script.js


### Css used:

* bootstrap.css
* style.css
* lightgallery.css


### Image folders:
* *images folder* needs to be uploaded and contains images used throughout the site.
* *pics folder* contains dummies for the flat html pages.
* *photos folder* contains dummies for the flat gallery pages.
