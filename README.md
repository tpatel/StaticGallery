StaticGallery
=============

Generate a html gallery from the images in a directory.

Usage
-----

./generateGallery output.html template.html imageFolder/

You have to put the tag `/*STATIC_GALLERY*/` in your template `template.html`.
Then the script will create a new file, the tag being replaced by the javascript array containing all the files in the `imageFolder/` directory.
And voila !

Disclamer
---------
We don't own the photos, we took them from the good placeholder website : http://placedog.com/ by Jon Gaudette.
