![Sliding swipe menu preview](http://joanclaret.github.io/sliding-swipe-menu/demo/img/swipe-github.png)


Sliding swipe menu
========================================
A sliding menu that works with [touchSwipe](http://labs.rampinteractive.co.uk/touchSwipe/) library.


Online demo
-----------
Visit [plugin site](http://joanclaret.github.io/sliding-swipe-menu)  or  [online demo](http://joanclaret.github.io/sliding-swipe-menu/demo/index.html)  


What's the difference with other sliders?
-----------

This plugin uses CSS3 transform property to move the navigation. That's why it works smoothly. Because [performance matters](http://perf.rocks/).

* Only 1 js file (+ jQuery + touchSwipe)
* 2Kb minified


Installation
-----------

### 1. Grab a copy of the plugin

Using bower

```bash
bower install --save sliding-swipe-menu
```

Using npm

```bash
npm install sliding-swipe-menu
```

or [download the plugin](https://github.com/JoanClaret/sliding-swipe-menu/archive/master.zip) from GitHub


### 2. Load the required files

```html
<!-- jQuery library (served from Google) -->
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>

<!-- touchSwipe library -->
<script src="http://labs.rampinteractive.co.uk/touchSwipe/jquery.touchSwipe.min.js"></script>

<!-- Sliding swipe menu javascript file -->
<script src="../jquery.slidingswipemenu.js"></script>
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
        $('nav').slidingSwipeMenu();
    });
</script>
```


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
