## Image Gallery Example
This is just a tiny example of what an image gallery could be made to look and function like, using only css.

It uses a trick where it checks for active radio inputs (hidden via css) as a "lock" in order to change the background of the displayed image. You click the paired label to flip between radios.

This was made with the thought of it being used in a workflow such as handlebars/mustache/etc., where you could have a pre-defined array of images generating the markup (hence the style tag with all the `nth-of-type`s in the markup).

Radio buttons have to come first in the markup, for this to work.

Code is commented with more information.
