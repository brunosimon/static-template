# Static template

Simple static HTML/CSS/JS template

### Features

- Gulp
- ES2015 transpiler
- Stylus compiler
- Sourcemaps
- Watchers
- Static server
- Assets syncing
- Errors handling
- Notifications
- Builder

### Usage

- Install [Node.js](https://nodejs.org/en/)
- Open the terminal
- Install [gulp-cli](https://www.npmjs.com/package/gulp-cli) in global using `npm install -g gulp-cli` (You may need to start with `sudo`)
- In the terminal, go to the `builder/` folder
- Install dependencies using `npm install` (You may need to start with `sudo`)
- Start the server with `gulp`
- A page with `It's alive` alert should show up

### Gulp tasks

- `scripts` to transpile javascript and start watching scripts
- `styles` to compile CSS
- `serve` to start the server
- `build-scripts` to compress the scripts
- `build-styles` to compress the styles
- `remove-maps` to remove both scripts and style sourcemaps
- `build` to launch `build-scripts`, `build-styles` and `remove-maps`
- `default` to launch `scripts`, `styles`, watchers and `serve`

### Todo

- [ ] Seperate scripts compiler from script watcher
- [ ] Add params objet in gulpfiles, mostly for pathes