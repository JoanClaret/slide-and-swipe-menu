![Slide and swipe menu preview](http://joanclaret.github.io/slide-and-swipe-menu/demo/img/swipe-github-demo.png)


Slide and swipe menu
========================================
A sliding menu that works with [touchSwipe](http://labs.rampinteractive.co.uk/touchSwipe/) library.


Online demo
-----------
Visit [plugin site](http://joanclaret.github.io/slide-and-swipe-menu).

[Appszoom](http://www.appszoom.com) also uses it! So cool!



What's the difference with other sliders?
-----------

This plugin uses CSS3 transform property to move the navigation. That's why it works smoothly. Because [performance matters](http://perf.rocks/).

* Only 1 js file (+ jQuery + touchSwipe)
* 1Kb minified


Installation
-----------

### 1. Grab a copy of the plugin

Using bower

```bash
bower install slide-and-swipe-menu --save
```

Using npm

```bash
npm install slide-and-swipe-menu --save
```

or [download the plugin](https://github.com/JoanClaret/slide-and-swipe-menu/archive/master.zip) from GitHub


### 2. Load the required files

Load them in the html

```html
<!-- jQuery library (served from Google) -->
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>

<!-- touchSwipe library -->
<script src="http://labs.rampinteractive.co.uk/touchSwipe/jquery.touchSwipe.min.js"></script>

<!-- Sliding swipe menu javascript file -->
<script src="../jquery.slideandswipe.js"></script>
```

or use Browserify

```javascript
require('slideAndSwipe');
```


### 3. Create the HTML markup

```html
 <body>
    <nav>
        [...]
    </nav>
    <main>
        [...]
        <a class="ssm-open-nav" href="#" title="Open / close">Open / close</a>
    </main>
</body>
```


### 4. Initialize the plugin

Default initialization

```javascript
<script>
    $(document).ready(function() {
        $('nav').slideAndSwipe();
    });
</script>
```

### 5. Follow the repository
★ Star and watch [this repo](https://github.com/JoanClaret/slide-and-swipe-menu) in order to stay updated with news about this plugin


License
-------

    The MIT License (MIT)

    Copyright (c) 2015 Joan Claret

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
