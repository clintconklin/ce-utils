# CreativEngine Development Utilities

A gulp-based less/js compilation and minification utility that's geared towards the CreativEngine development environment.

## Installation

1. Clone the repo
2. If you don't have it already, install npm via the node install @ https://nodejs.org/
3. Make sure gulp is installed globally: `npm install -g gulp`; note that while `sudo` is fine for gulp, as a general practice [you really shouldn't use it to install modules globally](https://docs.npmjs.com/getting-started/fixing-npm-permissions).
4. From the repo directory, run `npm install`

## Running

1. Navigate to the cloned directory
2. Type `gulp ce-utils --env [environment]`; e.g. `gulp ce-utils -env senx`

Alternately, you can add an alias to your .bash_profile/.bashrc like so (the example below assumes you've cloned the ce-utils folder into your user directory):

`alias ce-utils='cd ~/ce-utils/;gulp ce-utils'`

Then invoke via `ce-utils --env [environment]`; e.g. `ce-utils -env senx`

Note that for now the only included environments are `senx` and `amend-tinymce`; for custom environment configuration, rename the included `config-SAMPLE.js` as `config.js` and modify as needed

That's it!
