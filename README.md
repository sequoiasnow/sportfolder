# SportsFolder Splashpage

The sportsfolder splashpage is a simple html and css page that uses 
features of nodejs to compile a simple static website. All data 
for the website is stored in the `./data` directory as markdown files
and an overall json file which contains smaller information. 

The required files for the project are described in the README file of
the data directory.


## Installation

To start clone this repository, to compile static assets then run 

```
npm install
npm run build
```

All assets will be compiled to the `./static` folder. To view the 
completed project simply open `./static/index.html`


## Development

For development clone the project, then run

```
npm install
npm run development
```

All changes are autoloaded using live-reload. The css files are compiled
from sass located in `./sass`.
