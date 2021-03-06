## My Resume

Inspired by Joyee Cheung, read resume data from a JSON file and generate a static web page, written with Gulp, Less, and Jade(Pug). 

GitHub Pages support included.

## Build

1. Run `npm init` to install the dependencies and init the `resume.json` according to `resume-sample.json`. 
2. Fill your own info to `resume.json`.
3. Run `npm run build` to generate the static web page(`dist/index.html`).
4. Run `npm run server` and visit `http://localhost:8000` if you want to see it hosted locally(make sure the port 8000 is not taken).

## Deploy to GitHub Pages

1. Set up the SSH git remote `origin` for the project.
2. After building the web page, run `npm run deploy`.
3. Everything under `dist` will be pushed to the remote repo's `gh-pages` branch.

## Develop

1. Make sure port 35729(for livereload) and 8000(for the local server) are available.
2. Run `npm run gulp`, then visit `http://localhost:8000`.
3. Start development!

## Advanced Usages
### Special Syntax In `resume.json`
* markdown link syntax: `[content](specific_url)`
* markdown strong syntax: `*{strong_content}*` or ``` `{strong_content}` ```

### CLI Augments
* `npm run deploy -m "commit message"`: edit customized commit message.

## Todo
- [ ] auto pdf generated mechanism

## LICENSE

(MIT License)

Copyright (c) 2015 Joyee Cheung

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
