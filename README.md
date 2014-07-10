# CSS FILTER BLUR

  Mobile-first classes for css-filter-blur.
  Set the desired css-filter-blur on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-filter-blur
```
or download the css on github and include in your project.

## File Size


## The Code
```
.blur1 { filter: blur(1px); }
.blur2 { filter: blur(.125rem); }
.blur3 { filter: blur(.25rem); }
.blur4 { filter: blur(.5rem); }
.blur5 { filter: blur(1rem); }

@include break(not-small) {
  .blur1-ns { filter: blur(1px); }
  .blur2-ns { filter: blur(.125rem); }
  .blur3-ns { filter: blur(.25rem); }
  .blur4-ns { filter: blur(.5rem); }
  .blur5-ns { filter: blur(1rem); }
}

@include break(medium) {
  .blur1-m { filter: blur(1px); }
  .blur2-m { filter: blur(.125rem); }
  .blur3-m { filter: blur(.25rem); }
  .blur4-m { filter: blur(.5rem); }
  .blur5-m { filter: blur(1rem); }
}

@include break(large) {
  .blur1-l { filter: blur(1px); }
  .blur2-l { filter: blur(.125rem); }
  .blur3-l { filter: blur(.25rem); }
  .blur4-l { filter: blur(.5rem); }
  .blur5-l { filter: blur(1rem); }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

