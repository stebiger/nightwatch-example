# nightwatch-example
Simple example project with all you need to get [nightwatchJS](https://github.com/nightwatchjs/nightwatch) up and running

# Shipping
This example project ships a stable `selenium server standalone jar in v. 2.52.0` and a `chromedriver release 2.21` for mac and windows (zip).
It also includes a mac/linux runner command so you don't need to use that `node_modules/nightwatch/bin/nightwatch` "shortcut" 
if you do not install nightwatch globally.
See the nightwatchjs.org Developer Guide if you need that for windows.

# Installation
If you do not already have nightwatch installed globally you can install this example package with `npm install`.
Anyhow you can also install nightwatch globally and just use the ready-to-use configuration set from this repo.

# Configuration
Nightwatch is configured to use the shipped selenium server and start the server itself when running tests.
The Page Objects will go to `pages/` and the `tests` should be under tests/ - anyhow this is customizable for your own needs and taste.

# Acknowledgements
* Thank you nightwatchJS Team for bringing this great UI-Testing Tool Framework and constantly developing it.
* I would also like to thank one of my customers who came up with nightwatch after evaluating different projects - from what I have seen until today, 
nightwatchJS really impressed me on many levels.
