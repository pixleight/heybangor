# #HeyBangor

HeyBangor uses Foundation, Grunt, Libsass, and Assemble!

## Requirements

You'll need to have the following items installed before continuing.

  * [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
  * [Grunt](http://gruntjs.com/): Run `sudo npm install -g grunt-cli`
  * [Bower](http://bower.io): Run `sudo npm install -g bower`

## Quickstart

Clone this repository:
`git clone git@github.com:pixleight/heybangor.git`

Navigate into the directory:
`cd heybangor`

Install all the dependincies:
`npm install && bower install`

While you're working on your project, run:

`grunt`

This will assemble all the pages and compile the Sass. You're set!

If you'd like to build project files whenever a change is detected, run:

`grunt watch`

Grunt will look for saved files in the `src` directories and build when needed.

## Directory Structure

* `/`: Static pages are assembled here. Pages in `src/pages` are built with `src/layouts/default.html` as a wrapper, and assembled into the root directory. **Don't edit these files directly. They will be overwritten!**
* `assets`: Javascript & CSS files are assembled here. **Don't edit these files directly. They will be overwritten!**
* `src`: This is the directory you'll work in.
* `src/assets`: All assets (scss, images, fonts, js, etc) go here.
* `src/assets/scss/_settings.scss`: Foundation configuration settings go in here. Uncomment lines & edit as needed to overwrite default settings.
* `src/assets/scss/app.scss`: Application styles go here

# TODO

* **Add Facebook hashtag stream.** Right now, Facebook's API doesn't allow searches for hashtags, so it's either find a workaround or hurry up & wait for them to make it available.
* **Add Google+ hashtag stream.** Do people use Google+? I haven't even looked into seeing if this sort of stream is possible.
* **Add Instagram hashtag stream.** Probably lowest priority, since Instagram typically gets posted to Twitter or Facebook anyways.
