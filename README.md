
# TinyWebServer

This program is a web server that allows running php program from C.

After modification it can be compiled with the following command: 
```
gcc nweb23.c -o nweb23php
```
The php code doesn't need compilation.

## Requirements

For ubuntu 22.04: 
 * PHP: `sudo apt install php-cli`
 * GCC: `sudo apt install build-essential`

For other linux distributions install php 8.1 and gcc 11.3.0  (tested with those versions).

## Quick Start

Running TinyWebServer in linux console:

NOTE: It is recomended to compile it for 64 bits systems.

1- enter the folder with `cd TinyWebServerPHP/`

2- run nweb23php with `./nweb23php 35000 .`

first parameter is the port and second is the directory

3- see the web server by searching http://localhost:35000 in a browser ("localhost:PORT") 



