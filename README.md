Gexf4js - Powered by Protovis
=============

Usage
------------
Insert an IFRAME into your website, appending the GEXF File to the querystring of the gexf4js.html file. Check out the code below.

	<iframe id="gexf4js" src="gexf4js.html?url=demo.gexf" border="0" frameborder="0"></iframe>

Installing
--------
I suggest you keep the gexf4js library in the same directory as the GEXF file.

1. Copy all the files to a gexf4js folder
2. Copy the GEXF file to the folder
3. Make any modifications you wish to the gexf4js.html file (like linking jQuery)
4. Place the IFRAME tag on your page.

Files
--------
* gexf4js.html - use in an IFRAME. The URL to the GEXF file in the querystring (?url=).
* jquery-1.4.2.min.js - jQuery Library
* protovis-r3.2js - Protovis Library
* demo.gexf - __OPTIONAL__ - the GEXF File to load

Known Bugs
---------
* Doesn't work in Chrome.
* Graph occasionally freaks out.
* Firefox occasionally places all the nodes on top of each other.

Road Map
----------
* Works on ALL Browsers
* Graph Properties - Size, Interaction
* Node Properties - Labels, Colors, Mouseovers
* Protovis Visualization - Matrix Diagram Implementation
* Protovis Visualization - Arc Diagram Implementation