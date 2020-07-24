# go-fileserver
> A simple HTTP server to share files over same wifi via QRCode

# Installation
```
git clone https://github.com/prdpx7/go-fileserver
cd go-fileserver/fs-server
go build
# now just run the binary
./fs-server
```
# Usage
```
fs-server - A simple HTTP Server to share files on a network.
Usage: fs-server [OPTIONS] <dir-path>
Options:
	-h | --help - show this message
Example:
fs-server - serve files from current directory
fs-server /home/user/documents/ - serve files from given directory
```
# Demo
<img src ="./fs-server.gif">
