# hello world :)

An hello world example. :)

## A.) First usage

### A.1) installation

First install the friends of bash libraries (https://github.com/bjoern-hempel/friends-of-bash). In short:

```
user$ cd ~
user$ git clone git@github.com:bjoern-hempel/friends-of-bash.git && cd friends-of-bash
user$ sudo -E bin/install
user$ cd .. && rm -rf friends-of-bash
```

Check that the friends of bash libraries are available:

```
user$ friends-of-bash --version
friends-of-bash/v0.0.11
```

Now install this application:

```
user$ sudo -E friends-of-bash install "git@github.com:bjoern-hempel/hello-world.git"
```

### A.2) show version

```
user$ hello-world --version
v0.0.0
```

### A.3) show help

```
user$ hello-world --help

Usage: /usr/local/bin/hello-world [options...]
 -h,    --help                    Shows this help.

 -v,    --version                 Shows the version number.
```
