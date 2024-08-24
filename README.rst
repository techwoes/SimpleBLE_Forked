SimpleBLE
==========

The ultimate fully-fledged cross-platform library and bindings for Bluetooth Low Energy (BLE).

|Latest Documentation Status|

Overview
--------

The SimpleBLE project aims to provide fully cross-platform BLE libraries and bindings
for Python, Rust and C++, designed for simplicity and ease of use with a licencing scheme
chosen to be friendly towards commercial use. All specific operating system quirks
are handled internally to provide a consistent behavior across all platforms. The
libraries also provide first-class support for vendorization of all third-party
dependencies, allowing for easy integration into existing projects.

This repository offers the source code for the following related libraries:

* **SimpleBLE:** C++ cross-platform BLE library.
* **SimplePyBLE:** Python bindings for SimpleBLE. See the `SimplePyBLE`_ PyPI page for more details.
* **SimpleRsBLE:** Rust bindings for SimpleBLE. See the `SimpleRsBLE`_ Crates.io page for more details.
* **SimpleBluez:** C++ abstraction layer for BlueZ over DBus. (Linux only)
* **SimpleDBus:** C++ wrapper for libdbus-1 with convenience classes to handle DBus object hierarchies effectively. (Linux only)


Supported platforms
-------------------
=========== ============= =================================== =====
Windows     Linux         MacOS                               iOS
=========== ============= =================================== =====
Windows 10+ Ubuntu 20.04+ 10.15+ (except 12.0, 12.1 and 12.2) 15.0+
=========== ============= =================================== =====

**NOTE:** WSL does not support Bluetooth.

Projects using SimpleBLE
------------------------
Don't forget to check out the following projects using SimpleBLE:

* `GDSimpleBLE`_
* `BrainFlow`_
* `InsideBlue`_

Notes
----- 

Forked at 0.6.1, license switched to GPL with 0.7.0 

License
-------

All components within this project that have not been bundled from
external creators, are licensed under the terms of the `MIT Licence`_.

.. Links

.. _SimplePyBLE: https://pypi.org/project/simplepyble/

.. _SimpleRsBLE: https://crates.io/crates/simplersble

.. _MIT Licence: https://github.com/OpenBluetoothToolbox/SimpleBLE/blob/main/LICENCE.md

.. _Discord: https://discord.gg/N9HqNEcvP3

.. _ReadTheDocs: https://simpleble.readthedocs.io/en/latest/

.. |Latest Documentation Status| image:: https://readthedocs.org/projects/simpleble/badge?version=latest
   :target: http://simpleble.readthedocs.org/en/latest

.. Other projects using SimpleBLE

.. _GDSimpleBLE: https://github.com/jferdelyi/GDSimpleBLE
.. _BrainFlow: https://github.com/brainflow-dev/brainflow
.. _InsideBlue: https://github.com/eriklins/InsideBlue-BLE-Tool
