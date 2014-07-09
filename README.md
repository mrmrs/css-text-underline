# CSS TEXT UNDERLINE

  Mobile-first classes for css-text-underline.
  Set the desired css-text-underline on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-text-underline
```
or download the css on github and include in your project.

## File Size


## The Code
```
.tup-auto { text-underline-position: auto; }
.tup-u {    text-underline-position: under; }
.tup-l {    text-underline-position: left; }
.tup-r {    text-underline-position: right; }
.tup-ul {   text-underline-position: under left; }
.tup-ru {   text-underline-position: right under; }
.tup-i {    text-underline-position: inherit; }

@include break(not-small) {
  .tup-auto-ns { text-underline-position: auto; }
  .tup-u-ns    { text-underline-position: under; }
  .tup-l-ns    { text-underline-position: left; }
  .tup-r-ns    { text-underline-position: right; }
  .tup-ul-ns   { text-underline-position: under left; }
  .tup-ru-ns   { text-underline-position: right under; }
  .tup-i-ns    { text-underline-position: inherit; }
}

@include break(medium) {
  .tup-auto-m { text-underline-position: auto; }
  .tup-u-m    { text-underline-position: under; }
  .tup-l-m    { text-underline-position: left; }
  .tup-r-m    { text-underline-position: right; }
  .tup-ul-m   { text-underline-position: under left; }
  .tup-ru-m   { text-underline-position: right under; }
  .tup-i-m    { text-underline-position: inherit; }
}

@include break(large) {
  .tup-auto-l { text-underline-position: auto; }
  .tup-u-l    { text-underline-position: under; }
  .tup-l-l    { text-underline-position: left; }
  .tup-r-l    { text-underline-position: right; }
  .tup-ul-l   { text-underline-position: under left; }
  .tup-ru-l   { text-underline-position: right under; }
  .tup-i-l    { text-underline-position: inherit; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

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

