# before-after.js

### A simple and responsive image comparison slider 

Comparison sliders are nothing new. There are even pure CSS implementations that is nothing but short of amazing. However, I wasn’t able to find a truly responsive one that was simple enough for our needs. This gave me the chance (and excuse) to build one myself that can be used anywhere.

The [Medium article](https://medium.com/jotform-form-builder/making-a-responsive-image-comparison-slider-in-css-and-javascript-f3a691a9dd71) details each decision made along the way.

#### DEMO

- [Landing page usage](http://jotform.com/formscentral)  
- [Codepen Demo](http://codepen.io/bamf/pen/jEpxOX)

![Image comparison](https://d262ilb51hltx0.cloudfront.net/max/800/1*N43g_K5grRctYcudDi3gLQ.gif)


#### UPDATES
- Performance improvements (Feb, 2017)
- before-after is now a jquery plugin, special thanks to [@ramblex](http://github.com/ramblex/). Also CDN links updated and fixed a few issues.(Feb, 2016)
- I was finally able to remove the jQuery Mobile dependency and handle it with native events. If you wish to help, mobile testing is much appreciated since I can only test a limited number devices. (March, 2015)

#### DEPENDENCIES
- [jQuery](http://jquery.com) for ease

#### USAGE
    $('.ba-slider').beforeAfter();
    
Or you can simply copy the contents of the sample.html to your own page. All links are called from a CDN.


#### LICENSE

The MIT License (MIT)
Copyright (c) 2015 JotForm
