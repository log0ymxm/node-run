Node-Run
========

A quick little tool to run a list of shell commands synchronously in node

Example usage:
--------------

    var run = require('run').run;
    run(
        'sudo apt-get install git-core',
        'mkdir ~/src',
        'cd ~/src',
        'git clone http://github.com/nrub/firstleft'
    );

Install with:
-------------

    npm install run
