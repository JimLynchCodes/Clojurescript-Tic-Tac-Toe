# Jim Tac Toe

## Live Demo

...

A remake of timothy Pratley's tic-tac-toe ClojureScript/ Reagent tutorial.

## Overview

This is a project scaffolded from `;lein new figwheel -- --reagent`.
The core logic of this project was developed by Timothy Pratley. I rebuilt the app by following along with his tutorial videos: (... and ...). I then added minor customizations to add my own flair to it. ;)

## Setup

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files (ie delete the "target" folder):

    lein clean

To create a production build run:

    lein cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Copyright © 2017

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
