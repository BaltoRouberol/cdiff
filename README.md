cdiff
=====

A simple colored diff. 
All added lines will be colored in green, and all suppressed lines will be colored in red,
using Git style (+/- instead of >/<).

You can also use all default `diff` options (see `man diff` or `diff --help`).

Installation
------------
Clone the repository, then
```bash
$ chmod +x diff
```

Usage
-----
```bash
$ cdiff file1 file2 [diff options]
```