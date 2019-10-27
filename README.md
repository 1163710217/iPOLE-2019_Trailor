<head>
Steps to deploy:
   
1) Download repo and $cd iPOLE

2) Install virtualenv, virtualenvwrapper, MongoDB, Node.js, LESS and UglifyJS.
   ---------------------------------------------
   || pip install virtualenv
   ||
   || # Read the docs for complete installation
   || pip install virtualenvwrapper
   ||
   || npm install less -g
   ||
   || npm install uglify-js -g
   ----------------------------------------------

3) Startup virtual environment and install dependencies
   ----------------------------------------------
   || virtualenv storymapjs
   || source storymapjs/bin/activate
   || pip install -r requirements.txt
   ----------------------------------------------

4) Build the project
   ----------------------------------------------
   || fab build
   ----------------------------------------------

5) run a simple local web server (like http-server) and load the following url (assuming your local server runs on port 8080)
   ----------------------------------------------
   || npm install http-server -g
   || # see usage: https://www.npmjs.com/package/http-server
   ----------------------------------------------
 </head>
