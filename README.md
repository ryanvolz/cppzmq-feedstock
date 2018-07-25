About cppzmq
============

Home: http://zeromq.org

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: C++ bindings for 0MQ



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/ryanvolz/cppzmq-feedstock/master.svg?label=Linux)](https://circleci.com/gh/ryanvolz/cppzmq-feedstock)
[![OSX](https://img.shields.io/travis/ryanvolz/cppzmq-feedstock/master.svg?label=macOS)](https://travis-ci.org/ryanvolz/cppzmq-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/ryanvolz/cppzmq-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/ryanvolz/cppzmq-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cppzmq-green.svg)](https://anaconda.org/ryanvolz/cppzmq) | [![Conda Downloads](https://img.shields.io/conda/dn/ryanvolz/cppzmq.svg)](https://anaconda.org/ryanvolz/cppzmq) | [![Conda Version](https://img.shields.io/conda/vn/ryanvolz/cppzmq.svg)](https://anaconda.org/ryanvolz/cppzmq) | [![Conda Platforms](https://img.shields.io/conda/pn/ryanvolz/cppzmq.svg)](https://anaconda.org/ryanvolz/cppzmq) |

Installing cppzmq
=================

Installing `cppzmq` from the `ryanvolz` channel can be achieved by adding `ryanvolz` to your channels with:

```
conda config --add channels ryanvolz
```

Once the `ryanvolz` channel has been enabled, `cppzmq` can be installed with:

```
conda install cppzmq
```

It is possible to list all of the versions of `cppzmq` available on your platform with:

```
conda search cppzmq --channel ryanvolz
```




Updating cppzmq-feedstock
=========================

If you would like to improve the cppzmq recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ryanvolz` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ryanvolz` channel.
Note that all branches in the ryanvolz/cppzmq-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.