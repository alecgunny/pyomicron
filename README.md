# PyOmicron
Python utilities and extensions for the Omicron (C++) GW event trigger generator, accessible in python via

```python
>>> import omicron
```

This package augments the core functionality of the Omicron ETG by providing utilities for building an HTCondor workflow (DAG) to parallelise processing, including segment-selection logic, frame-file discovery, and post-processing.

All credit for the actual Omicron algorithm goes to [Florent Robinet](//github.com/FlorentRobinet/), see [here](http://virgo.in2p3.fr/GWOLLUM/v2r2/index.html?Main) for more details.

## Requirements
This package is dependent upon the following packages

- [`numpy`](//numpy.org)
- [`gwpy`](//gwpy.github.io)
- [`glue`](//www.lsc-group.phys.uwm.edu/daswg/projects/glue.html)
- [`htcondor`](//research.cs.wisc.edu/htcondor/manual/v8.1/6_7Python_Bindings.html)
- [`PyROOT`](//root.cern.ch/pyroot)

## Project Status

[![Build Status](https://travis-ci.org/gwpy/pyomicron.svg?branch=master)](https://travis-ci.org/gwpy/pyomicron)
[![Coverage Status](https://coveralls.io/repos/github/gwpy/pyomicron/badge.svg?branch=master)](https://coveralls.io/github/gwpy/pyomicron?branch=master)

## License

PyOmicron is released under the GNU General Public License v3.0, see [here](https://choosealicense.com/licenses/gpl-3.0/) for a description of this license, or see [COPYING](https://github.com/gwpy/pyomicron/blob/master/COPYING) for the full text.
