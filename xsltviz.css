    /*

# The XSLTviz CSS stylesheet

## License for this stylesheet and its documentation

Copyright (c) 2013 Christian Gagné

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Purpose of this document

This style’s purpose is to help one vizualize the code of an XSLT stylesheet while writing or reviewing it.

XML syntax is notably verbose and, consequently, XSLT’s readability is not optimal. I decided to help myself understand my code by giving it an attractive visual design. This is inspired by the font-lock mode of Emacs and other such source code pretty-printers, but taken to a new level.

I make heavy (abusive?) use of `content` properties.

The documentation comments of this CSS stylesheet are written in Markdown, with all CSS indented by at least four spaces, so that a Markdown processor can treat the CSS file as if it was a Markdown file.

    */

    @namespace xsl url(http://www.w3.org/1999/XSL/Transform);

    stylesheet {
    display: block;
    background-color: grey;
    font-family: "Source Sans Pro", sans;
    }

    template {
    display: block;
    background-color: white;
    padding: 1em;
    border: 1px outset grey;
    margin: 1em;
    max-width: 36em;
    }

    template:before {
    content: "template (" attr(match) ") { ";
    font-size: 150%;
    color: #AAAAAA;
    }

    template:after {
    content: "}";
    font-size: 150%;
    color: #AAAAAA;
    }

    text {
    display: block;
    font-family: "PT Mono", monospace;
    }

    text:before {
    content: "Produce text: ";
    font-family: "Source Sans Pro", sans;
    color: #0080CC;
    }

    value-of {
    display: block;
    }

    value-of:before {
    content: "Select the value of: ";
    color: #0080CC;
    }

    value-of:after {
    content: attr(select);
    color: #00AA80;
    }

    apply-templates {
    display: block;
    }

    apply-templates:before {
    content: "• Apply templates recursively •";
    color: #0080CC;
    }