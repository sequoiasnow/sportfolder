# SportFolder Splashpage

The sportfolder splashpage is a simple html and css page that uses 
features of nodejs to compile a simple static website. All data 
for the website is stored in the `./data` directory as markdown files
and an overall json file which contains smaller information. 

The required files for the project are described in the README file of
the data directory.

## Installation

To start clone this repository, to compile static assets then run 

```
git clone https://github.com/the1codemaster/sportfolder.git
npm install
npm run build
```

All assets will be compiled to the `./static` folder. To view the 
completed project simply open `./static/index.html

## Development

For development clone the project, then run

```
npm install
npm run dev
```

All changes are autoloaded using live-reload. The css files are compiled
from sass located in `./sass`. **A server will start on port 3000**. Be sure 
to use the assets compiled by `npm run build` as it adds auto prefix support 
to the css.

## Development Options

`npm run build:css`

This will compile the static assets from `./sass` into `main.css` in the 
`static` directory. It also uses postcss autoprefixer to auto prefix css files.

---

`npm run build:html`

Creates the html file from templates and the data of `./data` directory. To 
read more about the data directory please view `./data/README.md`

---

`npm run build`

Builds both css and javascript resources.

---

`npm run watch:css`

Watches css files for changes and renders them on change. This only renders 
sass and does not prefix for older browser support, **only use in development**.

---

`npm run watch:html`

Watches the html and data files for changes and re-renders them on change.

---

`npm run serve`

Serves the static files using [express](https://expressjs.com) and then uses
[LiveReload](https://www.npmjs.com/package/livereload) to automatically update
on changes of the static directory. Starts a server on port 3000.

---

`npm run dev`

Watches changes to any files that would need compilation, starts a server and 
automatically reloads the server on changes to any source files. Best to use 
for development purposes.



