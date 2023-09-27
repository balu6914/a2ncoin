A2ncoin Core 0.14.2
=====================

Setup
---------------------
A2ncoin Core is the original A2ncoin client and it builds the backbone of the network. However, it downloads and stores the entire history of A2ncoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download A2ncoin Core, visit [a2ncoin.org](https://a2ncoin.org).

Running
---------------------
The following are some helpful notes on how to run A2ncoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/a2ncoin-qt` (GUI) or
- `bin/h2hcoind` (headless)

### Windows

Unpack the files into a directory, and then run a2ncoin-qt.exe.

### OS X

Drag A2ncoin-Core to your applications folder, and then run A2ncoin-Core.

### Need Help?

* See the documentation at the [A2ncoin Wiki](https://a2ncoin.info/)
for help and more information.
* Ask for help on [#a2ncoin](http://webchat.freenode.net?channels=a2ncoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=a2ncoin).
* Ask for help on the [H2hcoinTalk](https://h2hcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build A2ncoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The A2ncoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/a2ncoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [H2hcoinTalk](https://h2hcointalk.io/) forums.
* Discuss general A2ncoin development on #a2ncoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=a2ncoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
