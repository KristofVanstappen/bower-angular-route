<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="121px" viewBox="-0.5 -0.5 121 61" content="&lt;mxfile host=&quot;www.draw.io&quot; modified=&quot;2019-10-25T09:11:17.866Z&quot; agent=&quot;Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/77.0.3865.120 Safari/537.36&quot; etag=&quot;GSjg1YS5o0kGAB_RciI3&quot; version=&quot;12.1.5&quot; type=&quot;github&quot; pages=&quot;1&quot;&gt;&lt;diagram id=&quot;nwlnYesl4nnTbeu-sFTQ&quot; name=&quot;Page-1&quot;&gt;jZJLT4QwEMc/TY8mQHEXr4uLJsZXOJh4a+hIawrFbhHw01tkyiObTTx15jePTv8dQtOqvzOsEY+agyJRwHtCb0kUhXG0c8dIhons98kESiM5Ji0glz+AMEDaSg6nTaLVWlnZbGGh6xoKu2HMGN1t0z602t7asBLOQF4wdU7fJLdiosl1sPB7kKXwN4cBRirmkxGcBOO6WyF6JDQ1WtvJqvoU1Cie12Wqyy5E58EM1PY/BfxTvByyJ8ji9yR/eI6/XsviCrt8M9Xig3FYO3gFjG5rDmOTgNBDJ6SFvGHFGO3cnzsmbKWcFzoT24Gx0F+cM5xf79YGdAXWDC7FF3gFcWNu0O0W+UOvqVhJv0PG8MfLufMiijNQF+8u+v/FVltMj78=&lt;/diagram&gt;&lt;/mxfile&gt;" onclick="(function(svg){var src=window.event.target||window.event.srcElement;while (src!=null&amp;&amp;src.nodeName.toLowerCase()!='a'){src=src.parentNode;}if(src==null){if(svg.wnd!=null&amp;&amp;!svg.wnd.closed){svg.wnd.focus();}else{var r=function(evt){if(evt.data=='ready'&amp;&amp;evt.source==svg.wnd){svg.wnd.postMessage(decodeURIComponent(svg.getAttribute('content')),'*');window.removeEventListener('message',r);}};window.addEventListener('message',r);svg.wnd=window.open('https://www.draw.io/?client=1&amp;lightbox=1&amp;edit=_blank');}}})(this);" style="cursor:pointer;max-width:100%;max-height:61px;"><defs/><g><rect x="0" y="0" width="120" height="60" fill="#ffffff" stroke="#000000" pointer-events="none"/></g></svg>



# packaged angular-route

This repo is for distribution on `npm` and `bower`. The source for this module is in the
[main AngularJS repo](https://github.com/angular/angular.js/tree/master/src/ngRoute).
Please file issues and pull requests against that repo.

## Install

You can install this package either with `npm` or with `bower`.

### npm

```shell
npm install angular-route
```

Then add `ngRoute` as a dependency for your app:

```javascript
angular.module('myApp', [require('angular-route')]);
```

### bower

```shell
bower install angular-route
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/angular-route/angular-route.js"></script>
```

Then add `ngRoute` as a dependency for your app:

```javascript
angular.module('myApp', ['ngRoute']);
```

## Documentation

Documentation is available on the
[AngularJS docs site](http://docs.angularjs.org/api/ngRoute).

## License

The MIT License

Copyright (c) 2010-2015 Google, Inc. http://angularjs.org

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
