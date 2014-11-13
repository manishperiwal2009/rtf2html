rtf2html
========

Convert RTF texts to HTML tags.

Install
========
There are no prerequisite to install this module
```sh
npm install rtf2html
```

Example
========

```sh
var Rtf2Html = require(rtf2html);
```

```sh
var label = "\\\\rtf \\\\bf \\\\qc \\\\fs30 Welsome to the world of rich text format"

var labelHTML = Rtf2Html(("{\\rtf " + label + "}").replace(/\\\\/g, '\\'));
```

Api
========
Rtf2Html(doc, [options])

Future
========
In future version [options] will be filled with
 * Base URL for hyperlinks
 * Output object, will contain files to be written out.


License
========
BSD
