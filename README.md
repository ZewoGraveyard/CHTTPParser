CHTTPParser
==========

[![Swift 2.2](https://img.shields.io/badge/Swift-2.2-orange.svg?style=flat)](https://developer.apple.com/swift/)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://developer.apple.com/swift/)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](https://zewo-slackin.herokuapp.com/badge.svg)](http://slack.zewo.io)

**CHTTPParser** is an HTTP [(RFC 2616)](https://tools.ietf.org/html/rfc2616) parser for **Swift 2.2**.

## Installation

- Install [`http_parser`](https://github.com/Zewo/http_parser)

### Homebrew
```bash
$ brew tap zewo/tap
$ brew install http_parser
```

### Ubuntu/Debian
```bash
$ echo "deb [trusted=yes] http://apt.zewo.io/deb ./" | sudo tee --append /etc/apt/sources.list
$ sudo apt-get update
$ sudo apt-get install http_parser
```

### Source
```bash
$ git clone https://github.com/Zewo/http_parser.git && cd http_parser
$ make
$ (sudo) make install
```

- Add `CHTTPParser` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/CHTTPParser.git", majorVersion: 0, minor: 2)
	]
)

```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](http://slack.zewo.io)

Join us on [Slack](http://slack.zewo.io).

License
-------

**CHTTPParser** is released under the MIT license. See LICENSE for details.
