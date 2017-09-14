# About
Fork of the Adrien Friggeris CV template.

My version is typesetted in [Iwona](http://jmn.pl/en/kurier-i-iwona/) and
[Nanum Brush Script](http://hangeul.naver.com/) for a nifty sub heading. It
uses the roughly the same colours as the original. I also kept the `print`
option which renders in black and white, and reverts the header to dark on
light but hope noone really needs it.

Uses TikZ for the header, XeTeX and fontspec to use Iwona and Nanum Brush, biblatex for publications printing if needed and textpos for the aside and fontawesome for the social media icons in the sidebar. I changed the main font from Helvetica Neue Light to Open Sans Light.

I also included the font Iwona font archive from http://jmn.pl/en/kurier-i-iwona/ and Nanum Brush Script font from https://www.ffonts.net/Nanum-Brush-Script.font.

The original bibliography.bib file is remove because there is no  publication listing in my CV.

It is very handy to install all needed packages with `tlmgr`, the CTAN package
manager of the tex-live distribution:

``` sh
# fonts
tlmgr install iwona fontawesome lm-math

# needed packages, a lot of them may already be installed
tlmgr install textpos biblatex logreq unicode-math ucharcat filehook xstring
```

Compile the PDF with `lualatex cv.tex`

# License
Copyright (C) 2015, Norman Köhring
Copyright (C) 2012, Adrien Friggeri

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
