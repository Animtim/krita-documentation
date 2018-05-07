.. _map_filters:

===
Map
===

Filters that are signified by them mapping the input image.

Small Tiles
-----------

Tiles the input image, using it's own layer as output.

Phong Bumpmap
-------------

.. image:: /images/en/Krita-normals-tutoria_4.png

Uses the input image as a height-map to output a 3d something, using the phong-lambert shading model. Useful for checking one's height maps during game texturing. Checking the :guilabel:`Normal Map` box will make it use all channels and interpret them as a normal map.

Round Corners
-------------

Adds little corners to the input image.

Normalize
---------

This filter takes the input pixels, puts them into a 3d vector, and then normalizes(makes the vector size exactly 1) the values. This is helpful for normal maps and some minor image-editing functions.

Gradient Map
------------

.. image:: /images/en/Krita_filter_gradient_map.png

Maps the lightness of the input to the selected gradient. Useful for fancy artistic effects.

In 3.x you could only select predefined gradients. In 4.0, you can select gradients and change them on the fly, as well as use the gradient map filter as a filter layer or filter brush.
