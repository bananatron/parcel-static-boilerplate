# Static Site Boilerplate

For hosting static landing pages quickly, using [parcel.js](https://parceljs.org/).



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

This will build a `dist` folder/directory where the compiled markup, styles, and assets live. The `dist` directory will be used as the source for the deploy process below.



🚢 Deploy
-----
Host the `dist` folder on github pages or elsewhere (you might want to remove it from the `.gitignore` in order to do so).
