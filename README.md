# Build native binaries with GraalVM

This example shows how to use GraalVM to turn a Java application into a native binary using GraalVM's `native-image` tool.

Please read [Watch GraalVM Turn Your Java Into Binaries][blog-url] for a tutorial that shows you how to build this application.

**Prerequisites:** 
* [GraalVM](https://www.graalvm.org/downloads/)
* [Maven](https://maven.apache.org/download.cgi)

**Table of Contents**
* [Getting Started](#getting-started)
* [Help](#help)
* [Links](#links)
* [License](#license)

## Getting Started

This repository contains two examples (`jvm` and `javascript`), you can build each one using `mvn package`.

```bash
git clone https://github.com/oktadeveloper/okta-graalvm-example.git
cd jvm
mvn package
```

### Run the application

To start the application you can run:

```bash
./target/roll 2d20
```

## Links

This example uses the following libraries provided by Okta:

* [GraalVM](https://www.graalvm.org/)

## Help

Please post any questions as comments on [this blog post][blog-url], or visit our [Okta Developer Forums](https://devforum.okta.com/). You can also email developers@okta.com if would like to create a support ticket.

## License

Apache 2.0, see [LICENSE](LICENSE).

[blog-url]: http://developer.okta.com/blog/2019/11/27/graalvm-java-binaries
