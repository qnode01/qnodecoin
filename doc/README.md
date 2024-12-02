Qnodecoin
=============

Setup
---------------------
Qnodecoin is a Qnodecoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Qnodecoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Qnodecoin, visit [qnodecoinmore.org](https://qngnode.cc).

Running
---------------------
The following are some helpful notes on how to run Qnodecoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/qnodecoin-qt` (GUI) or
- `bin/qnodecoind` (headless)

### Windows

Unpack the files into a directory, and then run qnodecoin-qt.exe.

### OS X

Drag Qnodecoin-More.app to your applications folder, and then run Qnodecoin-More.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#qnodecoin](http://webchat.freenode.net?channels=qnodecoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=qnodecoin).
* Ask for help in [Qnodecoin room](https://gitter.im/Qnodecoin_Hub) on Gitter.
* Ask for help in [/r/qnodecoin/](https://nm.reddit.com/r/qnodecoin/) on Reddit.
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Qnodecoin topic](https://bitcointalk.org/index.php?topic=3017838.new#new).

Building
---------------------
The following are developer notes on how to build Qnodecoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Qnodecoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Qnodecoin topic](https://bitcointalk.org/index.php?topic=3017838.new#new).
* Discuss Qnodecoin development in [Qnodecoin room](https://gitter.im/Qnodecoin_Hub) on Gitter.
* Discuss Qnodecoin development in [Qnodecoin team](https://keybase.io/team/qnodecoin) on Keybase.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
