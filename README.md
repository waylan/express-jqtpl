Express App Template for jqtpl Templates
========================================

A  application template for the [Express] framework on 
[Node.js] which uses the [jqtpl] template engine. Known 
to work with Express version 2.5.2.

These are the files that the command `express -t jqtpl mydir`
would generate if express had full support built in for 
jqtpl. You will need to run `cd mydir && npm install` on a
fresh copy of this template to install dependencies.

Run `node app.py` to serve the "Welcome to Express" page at
"http://localhost:3000/".

Note that the 'logger' and 'favicon' middleware has been
added as well. Just comment out the appropriate lines in
'app.js' to disable.

[Express]: http://expressjs.com/
[Node.js]: http://nodejs.org
[jqtpl]: https://github.com/kof/node-jqtpl