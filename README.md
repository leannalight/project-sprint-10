# regexp-validation

## Current version 
v0.0.4

[**Link to this project on github pages**](https://leannalight.github.io/regexp-validation/)

This is my study project for practicing Git and form validation with regular expressions. Here I'm validating standard form inputs like name, email, phone number and url address.

## Requirements for form inputs:

### ```Name```
- cyrillic only
- capitalized first letter
- you can enter from 2 to 20 characters - this can be set in the minlength and maxlength attributes
- writing double names is possible - for example Anna-Maria

### ```Email```
- only latin
- ```@``` is required character
- dot ```.``` is also a required symbol
- numbers, underscore, dash are allowed characters

### ```Phone number```
The template for the phone should find numbers in the following formats:
```
+7(925)900-90-90
+7(925) 900-90-90
+7 925-900-90-90
+79259009090
89259009090
```
There may be spaces in the phone number.

### ```Website address```
The site address must:
- start with ```http://``` or ```https://```
- then ```www.``` is an optional group
- IP address - 255.255.255.255 or domain name - stasbasov.ru
- port is also an optional group. The port starts with a colon followed by 2 to 5 digits. For example: ```:8080```
- path - a sequence of numbers, slashes and Latin letters, at the end of which there may be a hash #
- the template should find url of the following formats:
```
http://ya.ru
https://www.ya.ru
http://2-domains.ru
http://ya.ru:98/
http://ya.com:30
http://ya.ru/path/to/deep/
http://ya-ya-ya.ru
http://8.8.8.8:8080
http://8.8.8.8:8080/page/to/deep#
```
## Technologies used in the project:
- HTML
- CSS
- Git

