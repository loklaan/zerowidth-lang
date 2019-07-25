# Whitespace Interpreter (modified to use [Zero Width](https://en.wikipedia.org/wiki/Zero_width) chars)

CLI to interpret programs written in the [Whitespace programming language](http://compsoc.dur.ac.uk/whitespace/), but modifed to use [Zero Width](https://en.wikipedia.org/wiki/Zero_width) characters ZEROWIDTH SPACE and ZEROWIDTH NON-JOINER.

## Usage

**Quick Start**

```shell
$ npx zerowidth-lang print-hello-world.zw
```

---

```shell
# Install
$ npm i -g zerowidth-lang

# Running a program
$ zerowidth print-hello-world.zw
$ Hello World!

# Also works with stdin!
$ cat print-hello-world.zw | zerowidth
$ Hello World!
```

## Contributing

This is a silly project, I won't be maintaining it for any real use case!

Saying that, feel free to make GitHub issues. 👍

## Legal

### Credit

**Thanks [vii5ard](https://github.com/vii5ard)!**
_The interpreter & compiler where adapted from the [vii5ard/whitespace](https://github.com/vii5ard/whitespace) IDE, which you should use to create programs!_

### License

MIT License

_Copyright (c) 2019 Lochlan Bunn_
