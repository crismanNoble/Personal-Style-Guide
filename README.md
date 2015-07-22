# Personal-Style-Guide
How I do things, for future reference.

##Saving data to a database
Anytime you put user supplied data into a database, it is imparitive that you perpare it properly. When using PHP + mySQL, the easiest way is to use `mysqli::real_escape_string()`[1]. However, since this will escape `"`, make sure to escape the double quotes, `\"`, when dumping the putput back to json.

[1: php.net](http://php.net/manual/en/mysqli.real-escape-string.php).
