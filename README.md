# Page Depth module documentation

_THE DOCUMENTATION IS STILL A WORK IN PROGRESS, AS IS THE MODULE_

$page->depth() -- Takes no argument, returns the page depth relative to root (/).

$page->depthFromClosest(selector) -- Takes a selector string, will return null if the function doesn't find a match.

$page->depthFromPage(selector|page object) -- Takes a page object or a selector string (usage same as `$pages->get()`), will return null if $page isn't a child of the passed in page object or selector.

## License

The MIT License (MIT)

Copyright (c) 2014 Pierre-Luc Auclair

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