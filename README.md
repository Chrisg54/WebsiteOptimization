# WebSite Optimization
## Summary
This site is optimized throught the following fixes:

## PageSpeed Score
### index.html Optimization
1. Move inline script above external scripts and styles
2. Add async to the google analytics script link
3. Comment out bad web font link
4. Move stylesheet styles inline
5. Add class names to elements for faster access

### style.css (added styles inline on index.html)
1. Remove unused styles
2. Replace parent-child element styles with specific class names
3. Remove media query enclosed styles to new file style-480.css
4. Minify files

## Getting Rid of Jank
### views/js/main.js
1. Simplied the change PizzaSizes function
2. Fix the layout thrashing in the updatePositions function
3. Minify file

##Setup
Run npm install in node to download all of the node packages for the project.

##Test
Run npm gulp in node to run the site locally.

##Distribute
Run npm dist in node to generate production ready files that are minified and concatenated.

## License

MIT License

Copyright (c) 2016 Chris Gomez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.