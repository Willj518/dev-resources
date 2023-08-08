
### Here’s a collection of one line commands that will start a local HTTP server for static files with node.js, PHP, Python (v2/v3), and ### Ruby.

`node.js`
Install http-server :

`$ npm install http-server -g`
Then execute the following from the root of the project:

`$ http-server -a localhost`
### PHP
`$ php -S localhost:8080 -t .`

### Python
Python 2.x
`$ python -m SimpleHTTPServer 8080`
Python 3.x
`$ python3 -m http.server 8080 --bind 127.0.0.1`
Ruby
`$ ruby -run -e httpd . -p 8080`
Create a Shell Alias
For simple reuse of any of the above one-liners, create a shell alias in your shell runcom file (e.g. .bashrc, .zshrc ):

`alias serve="python3 -m http.server 8080 --bind 127.0.0.1"`
Next, execute source on your shell runcom file. For bash:

`$ source ~/.bashrc`
Then navigate to the root of your project directory and enter:

`$ serve`
View Your Static Files in the Browser
Enter the following URL in your browser after using any of the above commands to start the local HTTP server: http://localhost:8080

Sources and Documentation
node.js
PHP
Python 2
Python 3
Ruby


