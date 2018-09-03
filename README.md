# Pacel Github Pages Boilerplate

For hosting static landing pages quickly, using [parcel.js](https://parceljs.org/) on Github pages.


Quickstart
-----
- `npm install -g parcel-bundler`
- `git clone`
- `npm install && npm start`


📦 Setup
-----
- Install [Node](https://docs.npmjs.com/getting-started/installing-node)
- Install [NPM](https://www.npmjs.com/get-npm)
- Install [Parcel](https://parceljs.org/)
- Run `npm install` in the directory with the `package.json` (the root directory).


⚡️ Build
-----
To 'compile' the files and continuously watch (in development mode), run `npm start` in the root directory. To stop the auto-reload listener, use `CTRL + C`.

This will build a `dist` folder/directory where the compiled markup, styles, and assets live.


🚢 Deploy
-----
Run `npm run build` to generate a `docs` folder with the parcel output. Host the `docs` folder on github pages or elsewhere. If hosting outside of github, you might want to add it to the gitignore and/or change the output file in the `package.json`.
