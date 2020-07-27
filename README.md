# ClickJackingScanner

Clickjacking works on python3. It uses the different libraries like argparse, os, threading, urllib, csv etc.
User have to give input file which contan list of all the urls or domains. Use can get subdomains of particular target by usig subbrute tool or aquatone and using this tool you can check for clickjacking vulnerability for thousands of domains within few seconds.


## Requirement
python3
Library of python: argparse, os, threading, urllib, csv, time

## How to run Clickjacking Scanner
python3 ClickJackingScanner.py -f <input_filename> -o <output_filename>

## How it works!!
It automatically travers to all the url and check for the clickjacking vulnerability. If tool find the vulnerability then it will store it into output file.

## PoC Video:
https://www.linkedin.com/posts/pranav-gajjar_python-ethicalhacking-wifijammer-activity-6693570944520208384-e3kx
