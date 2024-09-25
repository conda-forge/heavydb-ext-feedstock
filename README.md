About heavydb-ext-feedstock
===========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/heavydb-ext-feedstock/blob/main/LICENSE.txt)


About heavydb-ext
-----------------

Home: https://heavy.ai

Package license: Apache-2.0

Summary: The HeavyDB database

Development: https://github.com/heavyai/heavydb

Documentation: https://docs.heavy.ai/

HeavyDB is an in-memory, column store, SQL relational database
that was designed from the ground up to run on GPUs.

This recipe provides the following packages:
  heavydb-common CUDA-enabled heavydb, cpu and cuda builds
  pyheavydb Python connector
  heavydbe embedding library, cpu and cuda builds
  pyheavydbe-embedded Python extension module


About pyheavydb
---------------

Home: https://github.com/heavyai/heavydb

Package license: Apache-2.0

Summary: A python DB API 2 compatible client for HeavyDB (formerly OmniSci and MapD).

Development: https://github.com/heavyai/heavydb

Documentation: https://pyheavydb.readthedocs.io

A python DB API 2 compatible client HeavyDB (formerly OmniSci and MapD).


About heavydb
-------------

Home: https://heavy.ai

Package license: Apache-2.0

Summary: The HeavyDB database

Development: https://github.com/heavyai/heavydb

Documentation: https://docs.heavy.ai/

HeavyDB is an in-memory, column store, SQL relational database
that was designed from the ground up to run on GPUs.

This recipe provides both CUDA enabled and CUDA disabled heavydb
packages.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16451&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/heavydb-ext-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_c_compiler_version13cuda_compilerNonecuda_compiler_versionNonecxx_compiler_version13</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16451&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/heavydb-ext-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_c_compiler_version13cuda_compilerNonecuda_compiler_versionNonecxx_compiler_version13" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_cuda_compilerNonecuda_compiler_versionNone</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16451&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/heavydb-ext-feedstock?branchName=main&jobName=win&configuration=win%20win_64_cuda_compilerNonecuda_compiler_versionNone" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-heavydb-green.svg)](https://anaconda.org/conda-forge/heavydb) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/heavydb.svg)](https://anaconda.org/conda-forge/heavydb) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/heavydb.svg)](https://anaconda.org/conda-forge/heavydb) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/heavydb.svg)](https://anaconda.org/conda-forge/heavydb) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-heavydb--common-green.svg)](https://anaconda.org/conda-forge/heavydb-common) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/heavydb-common.svg)](https://anaconda.org/conda-forge/heavydb-common) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/heavydb-common.svg)](https://anaconda.org/conda-forge/heavydb-common) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/heavydb-common.svg)](https://anaconda.org/conda-forge/heavydb-common) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyheavydb-green.svg)](https://anaconda.org/conda-forge/pyheavydb) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pyheavydb.svg)](https://anaconda.org/conda-forge/pyheavydb) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/pyheavydb.svg)](https://anaconda.org/conda-forge/pyheavydb) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/pyheavydb.svg)](https://anaconda.org/conda-forge/pyheavydb) |

Installing heavydb-ext
======================

Installing `heavydb-ext` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `heavydb, heavydb-common, pyheavydb` can be installed with `conda`:

```
conda install heavydb heavydb-common pyheavydb
```

or with `mamba`:

```
mamba install heavydb heavydb-common pyheavydb
```

It is possible to list all of the versions of `heavydb` available on your platform with `conda`:

```
conda search heavydb --channel conda-forge
```

or with `mamba`:

```
mamba search heavydb --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search heavydb --channel conda-forge

# List packages depending on `heavydb`:
mamba repoquery whoneeds heavydb --channel conda-forge

# List dependencies of `heavydb`:
mamba repoquery depends heavydb --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating heavydb-ext-feedstock
==============================

If you would like to improve the heavydb-ext recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/heavydb-ext-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@guilhermeleobas](https://github.com/guilhermeleobas/)
* [@pantosik](https://github.com/pantosik/)
* [@pearu](https://github.com/pearu/)
* [@tmostak](https://github.com/tmostak/)
* [@tupui](https://github.com/tupui/)

