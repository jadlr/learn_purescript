# Basic Purescript Template Project for Experimentation

##### Make sure you have purescript installed

On Arch Linux:

* `pacman -S purescript`
* `npm install -g pulp bower`

##### Start coding

After you cloned this repo:

* `bower install`
* serve the `web` folder e.g. with `ruby -run -ehttpd . -p3000`
* live recompile your Purescript code `pulp --watch browserify --to ./web/static/js/app.js`

Now you should see changes in you Purescript on [localhost](http://localhost:3000/)
