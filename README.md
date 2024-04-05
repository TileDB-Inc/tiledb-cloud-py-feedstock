About tiledb-cloud-py-feedstock
===============================

Feedstock license: [BSD-3-Clause](https://github.com/TileDB-Inc/tiledb-cloud-py-feedstock/blob/main/LICENSE.txt)

Home: https://docs.tiledb.com/cloud/tutorials/start-here

Package license: MIT

Summary: TileDB Cloud platform Python client

Development: https://github.com/TileDB-Inc/TileDB-Cloud-Py

Documentation: https://tiledb-inc.github.io/TileDB-Cloud-Py/

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/TileDB-Inc/CI/_build/latest?definitionId=54&branchName=main">
        <img src="https://dev.azure.com/TileDB-Inc/CI/_apis/build/status/tiledb-cloud-py-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tiledb--cloud--py-green.svg)](https://anaconda.org/tiledb/tiledb-cloud-py) | [![Conda Downloads](https://img.shields.io/conda/dn/tiledb/tiledb-cloud-py.svg)](https://anaconda.org/tiledb/tiledb-cloud-py) | [![Conda Version](https://img.shields.io/conda/vn/tiledb/tiledb-cloud-py.svg)](https://anaconda.org/tiledb/tiledb-cloud-py) | [![Conda Platforms](https://img.shields.io/conda/pn/tiledb/tiledb-cloud-py.svg)](https://anaconda.org/tiledb/tiledb-cloud-py) |

Installing tiledb-cloud-py
==========================

Installing `tiledb-cloud-py` from the `tiledb` channel can be achieved by adding `tiledb` to your channels with:

```
conda config --add channels tiledb
conda config --set channel_priority strict
```

Once the `tiledb` channel has been enabled, `tiledb-cloud-py` can be installed with `conda`:

```
conda install tiledb-cloud-py
```

or with `mamba`:

```
mamba install tiledb-cloud-py
```

It is possible to list all of the versions of `tiledb-cloud-py` available on your platform with `conda`:

```
conda search tiledb-cloud-py --channel tiledb
```

or with `mamba`:

```
mamba search tiledb-cloud-py --channel tiledb
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search tiledb-cloud-py --channel tiledb

# List packages depending on `tiledb-cloud-py`:
mamba repoquery whoneeds tiledb-cloud-py --channel tiledb

# List dependencies of `tiledb-cloud-py`:
mamba repoquery depends tiledb-cloud-py --channel tiledb
```




Updating tiledb-cloud-py-feedstock
==================================

If you would like to improve the tiledb-cloud-py recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tiledb` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tiledb` channel.
Note that all branches in the TileDB-Inc/tiledb-cloud-py-feedstock are
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

* [@ihnorton](https://github.com/ihnorton/)
* [@jdblischak](https://github.com/jdblischak/)
* [@shelnutt2](https://github.com/shelnutt2/)

