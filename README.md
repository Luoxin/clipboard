[![Build Status](https://travis-ci.org/atotto/clipboard.svg?branch=master)](https://travis-ci.org/atotto/clipboard)

[![GoDoc](https://godoc.org/github.com/luoxin/clipboard?status.svg)](http://godoc.org/github.com/luoxin/clipboard)

# Clipboard for Go

Provide copying and pasting to the Clipboard for Go.

Build:

    $ go get github.com/luoxin/clipboard

Platforms:

* OSX
* Windows 7 (probably work on other Windows)
* Linux, Unix (requires 'xclip' or 'xsel' command to be installed)


Document: 

* http://godoc.org/github.com/luoxin/clipboard

Notes:

* Text string only
* UTF-8 text encoding only (no conversion)

TODO:

* Clipboard watcher(?)

## Commands:

paste shell command:

    $ go get github.com/luoxin/clipboard/cmd/gopaste
    $ # example:
    $ gopaste > document.txt

copy shell command:

    $ go get github.com/luoxin/clipboard/cmd/gocopy
    $ # example:
    $ cat document.txt | gocopy



