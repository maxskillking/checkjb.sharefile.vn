<h1 align="center">
  <img src="https://sharefile.vn/blog/wp-content/uploads/sites/2/2017/03/penguin.png"><br>
  <a href="https://checkjb.sharefile.vn/">checkjb.sharefile.vn</a>
</h1>

<p align="center">
  <a href="https://travis-ci.org/maxskillking/checkjb.sharefile.vn"><img src="https://travis-ci.org/cj123/canijailbreak.com.svg?branch=master" alt="Build Status"></a>
</p>

a website which tells you whether you can jailbreak your iPhone, iPad, iPod touch or Apple TV.

## Contributing

We welcome contributions to the code/design/data of the site! Currently, it's fairly basic.

A few guidelines for contributing:

1. **No beta jailbreaks**
2. **No beta iOS versions**
3. **Use one pull request per jailbreak addition** - this will allow us to easily approve/reject new additions on a one-by-one basis.
4. Commit tags for new jailbreaks, in the form of `[jailbreak] <name> <version> for <ios versions>` are recommended :)
5. Try to find the _simplest_ route to jailbreak, such as one click GUIs, that support _as many devices/ios versions as possible_.


## installation

```bash

$ go get github.com/maxskillking/checkjb.sharefile.vn
$ cd $GOPATH/src/github.com/maxskillking/checkjb.sharefile.vn
$ go build .
```

## running it

```bash
$ ./checkjb.sharefile.vn --help
```

This will generate output, by default into `./static`. 

## adding jailbreaks

look in the file `./jailbreaks.json` for a layout

then run the `./checkjb.sharefile.vn` util again
