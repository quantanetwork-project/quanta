Quanta Core
=============

Setup
---------------------
Quanta Core is the original Quanta client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Quanta transactions, which requires a few hundred gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Quanta Core, visit [quantanetwork.org](https://quantanetwork.org/download/).

Running
---------------------
The following are some helpful notes on how to run Quanta Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/quanta-qt` (GUI) or
- `bin/quantad` (headless)

### Windows

Unpack the files into a directory, and then run quanta-qt.exe.

### macOS

Drag Quanta Core to your applications folder, and then run Quanta Core.

### Need Help?

* See the documentation at the [Quanta Wiki](https://en.quanta.it/wiki/Main_Page)
for help and more information.
* Ask for help on [Quanta StackExchange](https://quanta.stackexchange.com).
* Ask for help on #quanta on Libera Chat. If you don't have an IRC client, you can use [web.libera.chat](https://web.libera.chat/#quanta).
* Ask for help on the [QuantaTalk](https://quantatalk.org/) forums, in the [Technical Support board](https://quantatalk.org/index.php?board=4.0).

Building
---------------------
The following are developer notes on how to build Quanta Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)

Development
---------------------
The Quanta repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.quantanetwork.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)
- [Internal Design Docs](design/)

### Resources
* Discuss on the [QuantaTalk](https://quantatalk.org/) forums, in the [Development & Technical Discussion board](https://quantatalk.org/index.php?board=6.0).
* Discuss project-specific development on #quanta-core-dev on Libera Chat. If you don't have an IRC client, you can use [web.libera.chat](https://web.libera.chat/#quanta-core-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [quanta.conf Configuration File](quantaconf.md)
- [CJDNS Support](cjdns.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [Managing Wallets](managing-wallets.md)
- [Multisig Tutorial](multisig-tutorial.md)
- [Offline Signing Tutorial](offline-signing-tutorial.md)
- [P2P bad ports definition and list](p2p-bad-ports.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Transaction Relay Policy](policy/README.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
