# phantomjs

Image based on pure Debian docker image.

basic phantomjs with all examples, mostly used for rasterize.js (screen capture) - SSL is being supported

Usage example for a screen-shot:
`docker run --rm -ti -v $PWD:/img rafal/screen_tmp phantomjs /e/rasterize.js https://github.com github.png`

All examples are located under `/e` directory and this is the full list,
a little description you can find here: http://phantomjs.org/examples/index.html and https://github.com/ariya/phantomjs/tree/master/examples


`arguments.js
child_process-examples.js
colorwheel.js
countdown.js
detectsniff.js
echoToFile.js
features.js
fibo.js
hello.js
injectme.js
loadspeed.js
loadurlwithoutcss.js
modernizr.js
module.js
netlog.js
netsniff.js
openurlwithproxy.js
outputEncoding.js
page_events.js
pagecallback.js
phantomwebintro.js
post.js
postjson.js
postserver.js
printenv.js
printheaderfooter.js
printmargins.js
rasterize.js
render_multi_url.js
responsive-screenshot.js
run-jasmine.js
run-jasmine2.js
run-qunit.js
scandir.js
server.js
serverkeepalive.js
simpleserver.js
sleepsort.js
stdin-stdout-stderr.js
universe.js
unrandomize.js
useragent.js
version.js
waitfor.js
walk_through_frames.js`
