This web project has the following setup:

* www/ - the web assets for the project
    * index.html - the entry point into the app.
    * js/ - the directory to hold scripts.
        * app.js - the top-level script used by index.html
        * app/ - the directory to store project-specific scripts. Any third
        party scripts should go in the js/ directory.
* tools/ - the build tools to optimize the project.

To optimize, run:

    tools/build.sh

This will create an optimized version of the project in a **www-built**
directory. The js/app.js file will be optimized to include all of its
dependencies.

For more information on the optimizer:
http://requirejs.org/docs/optimization.html

For more information on using requirejs:
http://requirejs.org/docs/api.html
