Class: Flickrbadge {#Flickrbadge}
=================================

This plugin MooTools allows you to create an unobtrusive interactive Flickr badge for your website or blog.

Flickrbadge Method: constructor {#Flickrbadge: constructor}
-----------------------------------------------------------

### Syntax:

    var flickr = new Flickrbadge(options)

### Arguments:

1. options (*Object*) An object containing the Flickrbadge instance's options.

#### options:

- containerClass  (``String`` default to 'flickrbadge') this class allows us to recognize that DIVs are for badges.
- openClass       (``String`` default to 'flickrbadgeopen') the class for open/close large image.
- originClass     (``String`` default to 'flickrlink') added this class to origin src (ex:$(src).addClass(this.options.originClass); in init).
- listClass       (``String`` default to 'flickritems') the class for list of images.
- bigImageClass   (``String`` default to 'flickrimage') the class for preview image.
- CSSURL          (``String`` default to 'flickrbadge.css') the whole badge can be styled by you, just change this CSS file.
- prevHTML        (``Object`` defalt to '&lt;img src="la.gif" alt="prev"/&gt;') the image for prev control.
- nextHTML        (``Object`` defalt to '&lt;img src="ra.gif" alt="next"/&gt;') the image for next control.
- seeAllLabel     (``String`` default to 'see all photos') the text for the label bottom right.
- navClass        (``String`` default to 'flickrnav') the class for the navigate controls.
- currentClass    (``String`` default to 'current') the class for the current list photos.

### Returns:

(*Object*) This instance of Flickrbadge.
