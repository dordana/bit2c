# bit2c
A node.js module for accessing bit2c (the Israeli bitcoin exchange) API.

## Installing

<pre><code>
npm install bit2c
</code></pre>


## Running the tests

If you want to run the tests that require access to the private API you should define 2 environment variables:
* BIT2C_KEY - your bit2c key
* BIT2C_SECRET - your bit2c key

These keys can be taken from your bit2c account. Just login -> API tab -> generate new.

Warning! - these keys grant access to your bit2c account! keep them safe!

For running the tests just clone the repository and then:
<pre><code>
npm install
npm test
</code></pre>

## License
(The MIT License)

Copyright (c) 2014 Ofer Eliassaf <ofer.eliassaf@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
