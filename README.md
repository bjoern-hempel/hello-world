# hello world :)

An hello world example. :)

## A.) First usage

### A.1) installation

This application uses the friends of bash libraries (https://github.com/bjoern-hempel/friends-of-bash). Check that the libraries are available:

```
user$ friends-of-bash --version
friends-of-bash/v0.0.31
```

If you can see a similar friends of bash version output like above, you can now install this application:

```
user$ sudo -E friends-of-bash install "git@github.com:bjoern-hempel/hello-world.git"
```

If you don't have installed the friends of bash libraries, please install them first. In short:

```
user$ cd ~ && git clone git@github.com:bjoern-hempel/friends-of-bash.git && cd friends-of-bash
user$ sudo -E bin/install
user$ cd .. && rm -rf friends-of-bash
```

## 1.) Usage

### 1.1) Show the version number (`--version`)

```
user$ hello-world --version
hello-world/v1.0.3
```

or

```
user$ friends-of-bash version hello-world
hello-world/v1.0.3
```

### 1.2) Update this application

```
user$ friends-of-bash update hello-world [-y]
```

### 1.3) Show the help dialog (`--help`)

```
user$ hello-world --help

Usage: /usr/local/bin/hello-world [options...]
 -h,    --help                    Shows this help.

 -v,    --version                 Shows the version number.
```

### 1.4) Execute hello-world

```
user$ hello-world
[2017-06-04 23:04:26] [HEADER‧] HELLO WORLD! :)
```

## B.) License

MIT © [Björn Hempel](https://www.ixno.de/hello-world)

Have fun! :)
