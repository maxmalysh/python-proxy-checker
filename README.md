# python-proxy-checker
## Description
Simple multithreaded proxy checker. Takes several text files as inputs.

## Usage
The script looks for all .txt files in some directory named "in_directory", takes all the proxies out, checks them and then puts the result to the file named "out_filename".
The input format is "ip:port" (e.g., "127.0.0.1:8080").

in_directory = './input/'
out_filename = 'output/out_filtered.txt'


For example:
`
python-proxy-checker
|-- proxy.py
|
|-- README.md
|
|-- input
|   |-- first.txt
|   |-- second.txt
|   |-- third.txt
|
|-- output
    |-- out_filtered.txt
`
