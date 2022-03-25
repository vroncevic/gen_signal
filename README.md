<img align="right" src="https://raw.githubusercontent.com/vroncevic/gen_signal/dev/docs/gen_signal_logo.png" width="25%">

# Generate Signal

**gen_signal** is tool for generation of signal modules.

Developed in **[python](https://www.python.org/)** code.

The README is used to introduce the modules and provide instructions on
how to install the modules, any machine dependencies it may have and any
other information that should be provided before the modules are installed.

![Python package](https://github.com/vroncevic/gen_signal/workflows/Python%20package%20gen_signal/badge.svg?branch=master) [![GitHub issues open](https://img.shields.io/github/issues/vroncevic/gen_signal.svg)](https://github.com/vroncevic/gen_signal/issues) [![GitHub contributors](https://img.shields.io/github/contributors/vroncevic/gen_signal.svg)](https://github.com/vroncevic/gen_signal/graphs/contributors)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Installation](#installation)
    - [Install using pip](#install-using-pip)
    - [Install using setuptools](#install-using-setuptools)
    - [Install using docker](#install-using-docker)
- [Dependencies](#dependencies)
- [Generation flow of py module](#generation-flow-of-py-module)
- [Tool structure](#tool-structure)
- [Docs](#docs)
- [Copyright and Licence](#copyright-and-licence)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### Installation

![Install Python2 Package](https://github.com/vroncevic/gen_signal/workflows/Install%20Python2%20Package%20gen_signal/badge.svg?branch=master) ![Install Python3 Package](https://github.com/vroncevic/gen_signal/workflows/Install%20Python3%20Package%20gen_signal/badge.svg?branch=master)

Currently there are three ways to install tool
* Install process based on pip
* Install process based on setup.py (setuptools)
* Install process based on docker mechanism

##### Install using pip

Python package is located at **[pypi.org](https://pypi.org/project/gen-signal/)**.

You can install by using pip
```
# python2
pip install gen-signal
# python3
pip3 install gen-signal
```

##### Install using setuptools

Navigate to release **[page](https://github.com/vroncevic/gen_signal/releases/)** download and extract release archive.

To install modules, locate and run setup.py with arguments
```
tar xvzf gen_signal-x.y.z.tar.gz
cd gen_signal-x.y.z/
# python2
pip install -r requirements.txt
python setup.py install_lib
python setup.py install_data
python setup.py install_egg_info
# python3
pip3 install -r requirements.txt
python3 setup.py install_lib
python3 setup.py install_data
python3 setup.py install_egg_info
```

##### Install using docker

You can use docker to create image/container.

[![gen_signal docker checker](https://github.com/vroncevic/gen_signal/workflows/gen_signal%20docker%20checker/badge.svg)](https://github.com/vroncevic/gen_signal/actions?query=workflow%3A%22gen_signal+docker+checker%22)

### Dependencies

**gen_signal** requires next modules and libraries

* [ats-utilities - Python App/Tool/Script Utilities](https://vroncevic.github.io/ats_utilities)

### Generation flow of py module

Base flow of generation process

![Generation flow](https://raw.githubusercontent.com/vroncevic/gen_signal/dev/docs/gen_signal_flow.png)

### Tool structure

**gen_signal** is based on OOP.

Generator structure

```

```

### Docs

[![Documentation Status](https://readthedocs.org/projects/gen_signal/badge/?version=latest)](https://gen_signal.readthedocs.io/projects/gen_signal/en/latest/?badge=latest)

More documentation and info at
* [gen_signal.readthedocs.io](https://gen_signal.readthedocs.io/en/latest/)
* [www.python.org](https://www.python.org/)

### Copyright and Licence

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Copyright (C) 2021 by [vroncevic.github.io/gen_signal](https://vroncevic.github.io/gen_signal)

**gen_signal** is free software; you can redistribute it and/or modify
it under the same terms as Python itself, either Python version 2.x/3.x or,
at your option, any later version of Python 3 you may have available.

Lets help and support PSF.

[![Python Software Foundation](https://raw.githubusercontent.com/vroncevic/gen_signal/dev/docs/psf-logo-alpha.png)](https://www.python.org/psf/)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://psfmember.org/index.php?q=civicrm/contribute/transact&reset=1&id=2)
