# Python proxy checker
## Description
Simple multithreaded proxy checker. Takes several text files as input.

## Usage
The script looks for all .txt files in the directory named "input", takes all the proxies out, checks them and then puts the result to the file named "working.txt".
The input format is "ip:port" (e.g., "127.0.0.1:8080").

So, to change the input directory and the output file, you have to alter the following lines:
```
in_directory = './input/'
out_filename = 'output/working.txt'
```


For example:
```
proxy-checker
|-- proxy.py
|
|-- README.md
|
|-- input
|   |-- http.txt
|   |-- socks4.txt
|   |-- socks5.txt
|
|-- output
    |-- working.txt
```


## Credit to https://github.com/cloudcant/ for his scraper
https://github.com/cloudcant/cloud-scraper
