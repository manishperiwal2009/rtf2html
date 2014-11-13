rtf2html
========

Convert rtf texts to html format

example
========
```sh
var Rtf2Html = require(rtf2html);
```

If your text is in rtf format like
```sh
var label = "\\\\rtf \\\\bf \\\\qc \\\\fs30 Welsome to the world of rich text format"

var labelHTML = Rtf2Html(("{\\rtf " + label + "}").replace(/\\\\/g, '\\'));
```
