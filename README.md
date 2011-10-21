Innerscroll v0.1
=================
Thursday, October 21st 2011
Inspiration from Facebook, iOS and Jonathan Azoff

Innerscroll provides an automatically fading in/out scrollbar while maintaining 100% native scrolling behaviour including (but not limited to) native performance, native inertial motion (especially on Macs), native scrolling with keyboard arrow keys, etc. To achieve an absolutely native feel, I allow the browser to do the scrolling (unlike all other implementations I have found which override the the browser with overflow:hidden and move the content manually, thus losing the native feel) and create an artificial scrollbar which imitates the real one.


<http://www.alexcchow.com/innerscroll>

License
-------
Copyright 2011, Alexander Chow

Licensed under the MIT license

<https://github.com/jquery/jquery/blob/master/MIT-LICENSE.txt>

Usage
-----
`$(selector).innerscroll({
    destination: $(selector2)
    });`