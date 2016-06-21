# phantomjs

Image based on pure Debian docker image.

this is a basic phantomjs with all examples, mostly used for rasterize.js (screen capture) - SSL is being supported

Usage example for a screen-shot:

`docker run --rm -ti -v $PWD:/img Shellmaster/phantomjs phantomjs /e/rasterize-latest.js https://github.com github.png`

All examples are located under `/e` directory and to get the full list, you can execute this command:

`docker run --rm -ti -v $PWD:/img Shellmaster/phantomjs ls -1 /e`

More info you can find here: http://phantomjs.org/examples/index.html and https://github.com/ariya/phantomjs/tree/master/examples


