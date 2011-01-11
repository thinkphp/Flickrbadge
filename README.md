Flickrbadge
===========

This plugin MooTools allows you to create an unobtrusive interactive Flickr badge for your website or blog.

![Screenshot](http://farm6.static.flickr.com/5241/5345913316_2dbbb9b357.jpg)

How to use
----------

First you must to include the JS file in the head of your HTML document.

        #HEAD
        <script type="text/javascript" src="mootools-core.js"></script>

In your BODY:

        #BODY
        <div class="flickrbadge">
            <p><a href="http://www.flickr.com/photos/23455178@N06">My latest photos on flickr</a></p>
        </div>
        <div class="flickrbadge">
            <p><a href="http://www.flickr.com/photos/11414938%40N00">My latest photos on flickr</a></p>
        </div>
        <div class="flickrbadge">
            <p><a href="http://www.flickr.com/photos/56734388@N00">My latest photos on flickr</a></p>
        </div>

        <!-- insert flickrbadge dot js -->
        <script type="text/javascript" src="flickrbadge.js"></script>

### Notes:

* all you have to provide is a link to your Flickr stream or the tagged images with the ID in your stream as a text link with a DIV with the 
  class (*flickrbadge*) around it. Notice you need the ID - the thing with the @ in it - and not your clean URL. 
  If you don't know, use [http://idgettr.com/](http://idgettr.com/) to retrieve it. If there is no JavaScript available, all the visitor gets is a link to your flickr profile.
* the whole badge can be styled by you, just change the CSS to your needs.
* the only need to insert the SCRIPT once, and the best option is to add it to the end of the document, just before the closing BODY tag.
* the script is a single include and loads the style sheet and the class helps files on demand when they are needed.
* visitors can see your photos on the page and click the thumbnails to see the larger preview. You can style the the badge any way you like by changing the supplied CSS file.
* the options can be changed in any way you need.
* the sample looks as following:
  <div class="...class..."><p><a href="...@...">...text...</a></p></div>

  You can see the badge in action:
- [http://thinkphp.github.com/Flickrbadge/](http://thinkphp.github.com/Flickrbadge/)
- []()


### Requirements:

- MooTools Core 1.3