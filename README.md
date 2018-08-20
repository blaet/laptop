Laptop
======

[![Build Status](https://travis-ci.org/blaet/laptop.svg?branch=master)](https://travis-ci.org/blaet/laptop)

Laptop is a script to set up a macOS laptop.


Install
-------

Download the script:

```sh
curl --remote-name https://raw.githubusercontent.com/blaet/laptop/master/mac
```

Review the script (avoid running scripts you haven't read!):

```sh
less mac
```

Execute the downloaded script:

```sh
sh mac 2>&1 | tee ~/laptop.log
```

Optionally, review the log:

```sh
less ~/laptop.log
```
