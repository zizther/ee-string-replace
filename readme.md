# ExpressionEngine String Replace

 Sometimes you need to use PHP functions but don't want to
 enable PHP in the template. This plugin allows you to use 
 the PHP string replace function in an EE tag passing the
 pattern, replacement, and string to search as parameters. 
 
 With this plugin you can pass EE variables to the tag 
 which will process them and return the string with the 
 replaced text.
 
 This example replaces spaces in a string with a dash
 if the var is {title} use this in it's place.

    {exp:strrep pattern=" " replace="-" string="{title}"}


## Parameters
Use the following parameter to specify what the plugin should return.

### pattern=""
The value being searched for, otherwise known as the needle. An array may be used to designate multiple needles.

### replace=""
The replacement value that replaces found search values. An array may be used to designate multiple replacements.

### string=""
The string or array being searched and replaced on, otherwise known as the haystack.


## Changelog

### Version 1.0
- Initial release