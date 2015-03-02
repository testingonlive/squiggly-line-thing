#squiggly-line-thing

Messing around with the web audio API

- listen.html should work in any browsers where the api is implemented - http://caniuse.com/#feat=audio-api
- talk.html + talk.promise.html use prefixed wekit get user media at the moment
- listen.promise.html + talk.promise.html use promises. Code is nicer where it works.
- I've tested it in chrome.

@TODO clear request animation frame on finish
@TODO babeljs version
@TODO sort webkit prefix