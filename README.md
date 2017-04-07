# Interactive Previews
This is a repo of static preview pages for testing interactives outside of Preview and Composer. This can be expanded and updated to include any layouts from guardian.com that an interactive can be embedded within.

The intention is that this will simplify browser and device testing for:
* Internal Guardian teams who have to log into to Preview on every device or browser they need to test
* External providers who have no access to Composer or Preview

Because the code is being ripped from the live site, there may be some errors appearing in the console for requests or scripts that fail. These aren't crucial to the functioning of the preview and can be ignored.

Each preview page has been named for the layout type they cover. See below for details of available layouts and configuration options:

## Immersive Preview
### https://interactive.guim.co.uk/embed/labs/previews/immersive.html
To embed your interactive, add a # followed by the full URL of the boot.js to link above e.g.:
https://interactive.guim.co.uk/embed/labs/previews/immersive.html#https://interactive.guim.co.uk/next-gen/labs-boot/2016/sep/powershop-video-wall/boot.js

### Options
Add the following options as query parameters to the URL, keys only e.g.:
https://interactive.guim.co.uk/embed/labs/previews/immersive.html?glabs&largead#https://interactive.guim.co.uk/next-gen/labs-boot/2016/sep/powershop-video-wall/boot.js

* glabs - Adds the GLABS paid for bar to the top of the page
* largead - Replaces the standard 90px high ad banner with the larger 250px high ad banner
* noad - Removes ads from the page completely
