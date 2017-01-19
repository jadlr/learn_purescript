# Basic Purescript Template Project for Experimentation

##### make sure you have purescript installed

On Arch Linux:

* `pacman -S purescript`
* `npm install -g pulp bower`

##### serve the web folder

You could use WEBrick:


* in the `web` filder run `ruby -run -ehttpd . -p3000`

##### live recompile your Purescript code

Use `pulp` with the `--watch` option:

* `pulp --watch browserify --to ./web/js/app.js`
