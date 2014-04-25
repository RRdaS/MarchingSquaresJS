Marching squares outlines blobs of non-transparent pixels inside a bitmap.

This is a straight forward port from this excellent implementation by Phill Spiess:

http://devblog.phillipspiess.com/2010/02/23/better-know-an-algorithm-1-marching-squares/

This is a Javascript implementation designed to be used with Html5 Canvas.

Check out the code in marchingSquaresTest.html for usage example.

http://htmlpreview.github.io/?https://github.com/sakri/MarchingSquaresJS/blob/master/marchingSquaresTest.html


Here's a few codepen demos using it:

A visualization of the algo as it executes
http://codepen.io/sakri/full/aIirl

Text Edge Flare
http://codepen.io/sakri/full/vIKJp

Ghost text
http://codepen.io/sakri/full/zbqti

He-Man effect
http://codepen.io/sakri/full/wsiLC


Here's a demo that tackles "blobs with holes" as in getting the outline for characters such as "O" "8" "&" etc.
http://codepen.io/sakri/pen/LCrDe

If there is interest, I can include the required code in this repo (floodFill, basic threshold etc.)



Have a good day!