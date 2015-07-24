# Personal-Style-Guide
How I do things, for future reference.

##Editor
Sublime text, yay. Preferred user settings: https://gist.github.com/crismanNoble/fdda297e1dfa6fc7364f. 

Good packages:
* Expand Tabs on Save: https://packagecontrol.io/packages/Expand%20Tabs%20on%20Save
* EditorConfig: https://packagecontrol.io/packages/EditorConfig
* LESS Syntax Highlighting: https://packagecontrol.io/packages/LESS
* LESS/Handlebars Syntax: https://packagecontrol.io/packages/Monokai%20Extended
* Markdown Extended Syntax: https://packagecontrol.io/packages/Markdown%20Extended

##Great Ideas
####Use .editorconfig
Read more http://editorconfig.org, mine: https://gist.github.com/crismanNoble/d98c2571c0c0fa5af8f4
 
##Stuff I always have to look up
* boookmarklet boilerplate: https://gist.github.com/crismanNoble/c3ae7decc8c2b4224b00
* SimpleHTTP Server Syntax: ???

##Stuff that has biten me
###Saving data to a database
Anytime you put user supplied data into a database, it is imparitive that you perpare it properly. When using PHP + mySQL, the easiest way is to use `mysqli::real_escape_string()`[1]. However, since this will escape `"`, make sure to escape the double quotes, `\"`, when dumping the putput back to json.

[1: php.net](http://php.net/manual/en/mysqli.real-escape-string.php).

##Blindspots that need research
* Effectively using Digital Ocean
* Installing a SSL cert
* Knowing anything about mail servers

