Flat Rocks
=========

<img alt="RocksDB Logo" height="100" src="http://rocksdb.org/wp-content/themes/rocksdb/rocksdb.png">
_[Image © Copyright 2016, Facebook](http://rocksdb.org/)_

**Native LevelUP bindings to RocksDB**

## Installing RocksDB

```
apt-get update
apt-get -q -y install build-essential python libgflags-dev libsnappy-dev zlib1g-dev libbz2-dev

git clone git://github.com/facebook/rocksdb.git
cd rocksdb

make static_lib
make shared_lib
make install -e INSTALL_PATH=/usr
```

## Building and Dependencies

Flat Rocks dynamically links to librocksdb. To build this module, both the RocksDB headers and dynamic library must be in the system's build-path and library-path, respectively.

Run `npm install` to fetch dependencies and compile bindings.

## API and Usage

Flat Rocks is API compatible with LevelDOWN. See the [LevelDOWN documentation](https://github.com/Level/leveldown#leveldown) for details.

## Thanks

This project is forked from [LevelDOWN](https://github.com/Level/leveldown), a native binding for LevelDB. It is API compatible, and remains largely the work of LevelDOWN's contributors:

* Rod Vagg <r@va.gg> (https://github.com/rvagg),
* John Chesley <john@chesl.es> (https://github.com/chesles/),
* Jake Verbaten <raynos2@gmail.com> (https://github.com/raynos),
* Dominic Tarr <dominic.tarr@gmail.com> (https://github.com/dominictarr),
* Max Ogden <max@maxogden.com> (https://github.com/maxogden),
* Lars-Magnus Skog <ralphtheninja@riseup.net> (https://github.com/ralphtheninja),
* David Björklund <david.bjorklund@gmail.com> (https://github.com/kesla),
* Julian Gruber <julian@juliangruber.com> (https://github.com/juliangruber),
* Paolo Fragomeni <paolo@async.ly> (https://github.com/hij1nx),
* Anton Whalley <anton.whalley@nearform.com> (https://github.com/No9),
* Matteo Collina <matteo.collina@gmail.com> (https://github.com/mcollina),
* Pedro Teixeira <pedro.teixeira@gmail.com> (https://github.com/pgte),
* James Halliday <mail@substack.net> (https://github.com/substack)

## License and Copyright

Copyright © 2016 John Manero.

**Flat Rocks** is released and distributed under terms of the MIT license. See the included LICENSE.md file for more details.

**LevelDOWN** and **LevelUP** are the property of their respective contributers:

* **LevelDOWN** is licensed under the MIT license. All rights not explicitly granted in the MIT license are reserved. See the [LevelDOWN project](https://github.com/Level/leveldown/blob/master/LICENSE.md) for more details.
* **LevelUP** is licensed under the MIT license. All rights not explicitly granted in the MIT license are reserved. See the [LevelUP project](https://github.com/Level/levelup/blob/master/LICENSE.md) for more details.

**RocksDB** is distributed under the terms of the BSD License. It is the property Facebook, Inc. See the [RocksDB project](https://github.com/facebook/rocksdb/blob/master/LICENSE) for more details.
