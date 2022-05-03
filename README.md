## My Resume

Read resume data from a JSON file and generate a static web page. GitHub Pages support included.

Written with Gulp, Less, and Jade.

## Build

1. Run `npm install` to install the dependencies.
2. Fill your resume data in `resume.json`.
3. Run `gulp build` to generate the static web page(`dist/index.html`).
4. Run `gulp server` and visit `http://localhost:8000` if you want to see it hosted locally(make sure the port 8000 is not taken).

## Deploy to GitHub Pages

1. Set up the SSH git remote `origin` for the project.
2. After building the web page, run `gulp deploy`.
3. Everything under `dist` will be pushed to the remote repo's `gh-pages` branch.

## Develop

1. Make sure port 35729(for livereload) and 8000(for the local server) are available.
2. Run `gulp`, then visit `http://localhost:8000`.
3. Start development!

## LICENSE

(MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
