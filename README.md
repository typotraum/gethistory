# gethistory

little script for getting historical dates from wikipedia on the command line. 

usage:

```
# gethistory 1789
```

gets the english wikipedia information on the command line

```
# gethistory 1789 de
```
-> receive the german wikipedia information

you can also get the spanish (es), italian (it), french (fr), polish (pl), chinese(zh) if you like
```
# gethistory -333 it
```

gets the italian wikipedia text for the year 333 BC for example

##requirements

the script uses [jq](https://stedolan.github.io/jq/) for parsing the json response, [html2text](https://github.com/aaronsw/html2text) for formating the html on the console

on ubuntu/debian install requirements via

```
# sudo apt-get install jq html2text
```

##install the script

```
# git clone https://github.com/typotraum/gethistory/
# cd gethistory
# sudo cp gethistory /usr/bin/gethistory
# sudo chmod a+rx /usr/bin/gethistory
```
don't forget to work and have fun










