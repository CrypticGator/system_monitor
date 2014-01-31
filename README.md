# System Monitor
A multi-platform system monitor, it shows memory usage, cpu usage, file systems, processes and network interfaces through a web interface.

![Screenshot](http://i.imgur.com/4sam7XM.png, "Screenshot")

## System Support
Tested on the following systems:
- Linux
- FreeBSD
- OSX

## Installing
__Prerequisites__
- GNU autotools/libtool
- pkg-config

To compile run
```
git submodule init
git submodule update
make
```

This will compile all dependencies and sources.

To start the web server, run `./system_monitor`, that will start the server on port 3000.

## Todos
- Make compilation easier and more portable (maybe use autoconf and automake)
- A way to configure
  - User password
  - HTTP port
  - Refresh timeout
  - What information to display
- User auth
- Run as daemon
- Provide installers for common systems like debian
- Process detailed information
