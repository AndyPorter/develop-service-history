I want to develop property or land
==================================

Discovery, Alpha 1 & 2, Private Beta - service designs for the 'I want to develop property and land'.

## Intention

To show drawings and screenshots of: design ideas, completed designs, and snapshots of the running service.

Include notes of design intention, user needs, user feedback, changes made in response to insights.

[https://andyporter.github.io/develop-service-history/](https://andyporter.github.io/develop-service-history/)



## Running this app locally

The app is very simple and doesn't require anything to be installed or run in a terminal. Just open the index.html file in the root folder. It works especially well in Chrome's presentation mode. Your mileage may vary in other browsers.


## How to contribute

If you work on this service and want to add or update screenshots of it please go ahead. Pull requests are the best way. You'll need to know how to use Git and how to edit very simple data files.

### Capturing screenshots

On OSX, [Paparazzi](https://derailer.org/paparazzi/) is the best way to capture screenshots. You can set the maximum and minimum widths for the screens, and can capture images in batches.

[Nixon](https://github.com/joelanman/nixon) is a tool that allows you to automate screenshot capture using CasperJS or PhantomJS.

On Windows you can use the [Awesome Screenshot](https://chrome.google.com/webstore/detail/awesome-screenshot-captur/alelhddbbhepgpmgidjdcjakblofbmce?hl=en) plugin for Chrome.

You can also use services like [BrowserStack](http://www.browserstack.com/) or [Sauce Labs](https://saucelabs.com/) for automated serverside screenshot capture.

### 1. Add your images

Each 'point in time' - a version of the service, has it's own numbered folder in '/version'. Drop all your images into the 'images' subfolder (1024px wide is best).

v99 contains the current version of the service, to be added to as changes occur.  At a sensible point in time, make a snapshot of 99 with a lower number.

### 2. Update the data file

Edit the data.js file in your numbered version folder.

### 3. Update the index file

Once you're done, don't forget to add a link to your version from the 'index.html' file in the root of this repository (not the one in your numbered exemplar folder).


## Attribution

This tool is based on (and code cloned from) GDS Exemplar screens repo. 

### Code History

* https://github.com/LandRegistry/fpi-service-screens (code cloned from)
* https://github.com/AndyPorter/exemplar-screens
* https://github.com/claragt/exemplar-screens
* https://github.com/alphagov/exemplar-screens




