### plisteditor

This is a rough demo of a JavaScript-based plist editor.

A web app could use this -- the web app would send a plist as a string to the
browser. User could then view and/or edit the plist via the browser. If they 
chose to save their changes, the plist could be sent back as a string in a POST 
request.

The web app need only read and write plists as strings.

To play with the demo, open plisteditor.html in your browser.

For extra fun, paste a complex plist like a Munki manifest or a Munki pkginfo
file into the plist pane.

(Update: this evolved into the plist editor in MWA2: https://github.com/munki/mwa2)
