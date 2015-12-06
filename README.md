CHTTPParser
==========

[![Swift 2.2](https://img.shields.io/badge/Swift-2.2-orange.svg?style=flat)](https://developer.apple.com/swift/)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://developer.apple.com/swift/)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](https://zewo-slackin.herokuapp.com/badge.svg)](https://zewo-slackin.herokuapp.com)

**HTTP** [(RFC 2616)](https://tools.ietf.org/html/rfc2616) parser for **Swift 2.2**.

## Installation

- Install [`http_parser`](https://github.com/Zewo/http_parser)

```bash
$ git clone https://github.com/Zewo/http_parser.git
$ cd http_parser
$ make
$ dpkg -i http_parser.deb
```

- Add `CHTTPParser` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/CHTTPParser.git", majorVersion: 0, minor: 1)
	]
)

```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](https://zewo-slackin.herokuapp.com)

Join us on [Slack](https://zewo-slackin.herokuapp.com).

License
-------

**URI** is released under the MIT license. See LICENSE for details.
