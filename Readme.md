*This repository is a mirror of the [component](http://component.io) module [eivindfjeldstad/combobox](http://github.com/eivindfjeldstad/combobox). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eivindfjeldstad-combobox`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# combobox
A lightweight selectbox replacement. Built entirely with components, no jQuery or other frameworks. Comes with search functionality, keyboard navigation and other cool stuff.

![combobox component](http://f.cl.ly/items/131l0F0A3W3A2d312K1s/combobox.png)

## Installation
    $ component install eivindfjeldstad/combobox

## Example
```js
var Combo = require('combobox');
var combo = Combo({ search: true });

combo.group('Group 1')
  .add(1, 'Option 1')
  .add(2, 'Option 2');
  
combo.appendTo(document.body);
```

## API
TODO
  
## TODO
Make it easier to replace existing select elements

## License
The MIT License (MIT)

Copyright (c) 2014 eivindfjeldstad

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
