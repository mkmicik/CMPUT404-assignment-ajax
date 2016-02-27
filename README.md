CMPUT404-assignment-ajax
==============================

CMPUT404-assignment-ajax

See requirements.org (plain-text) for a description of the project.

Make a shared state AJAX drawing program

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

=============================
| 		 Alterations 		|
=============================
Author: 		Mike Kmicik
Date Modified: 	Feb. 27, 2016

Summary
==========
All of the sections marked 'XXX' have been completed. The application functions as expected. When one user draws on the canvas, the changes are immediately displayed to any other browsers connected to the server. The page polls the server 30 times per second, and requests the coordinates of points. The server returns the points and the page determines if they should be redrawn or not. The server correctly responds to all valid routes, including 'world/', 'entity/<entity>', and 'clear/'. 
To make the drawing 'prettier', I implented a function to randomly choose a color for each point upon creation. Similarly, the radius of each point grows or shrinks +/- 4 pixels relative to the previously drawn point. This has the effect of randomly shrinking and growing the size of the brushstroke. Finally, the circles are filled instead of outlined, and the fill color transparency is set to 30%. This achieves a relatively 'pretty' effect.

Know Issues
==========
There are no known issues with my implementation, all features should function as expected.

Collaboration
=============
I did not collaborate with any other students for this assignment.