Overview
----------------------
In this section we introduce the concept of creating a view from scratch.  Every Brightcove App Cloud app includes a manifest.json file and an HTML page.  In this section we add a new view of "hello", a HTML page that says "Hello World", and an icon for our native navigation.

Troubleshooting
---------------------

Make sure phone and computer are on the same network.
Make sure you did not use "localhost" in your webserver address.  Either use the name of your computer or the IP address.


Exploring
----------------

1.  Try changing the text of the HTML.
2.  Change the nativeNavigation to false in the manifest.json file.  (notice that the native navigation goes away.  On iPhone the tabbar, on android the options menu)