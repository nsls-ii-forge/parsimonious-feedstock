About parsimonious
==================

Home: https://github.com/erikrose/parsimonious/

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: (Soon to be) the fastest pure-Python PEG parser I could muster

(Soon to be) the fastest pure-Python PEG parser I could muster

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=117&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/parsimonious-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-parsimonious-green.svg)](https://anaconda.org/nsls2forge/parsimonious) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/parsimonious.svg)](https://anaconda.org/nsls2forge/parsimonious) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/parsimonious.svg)](https://anaconda.org/nsls2forge/parsimonious) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/parsimonious.svg)](https://anaconda.org/nsls2forge/parsimonious) |

Installing parsimonious
=======================

Installing `parsimonious` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `parsimonious` can be installed with:

```
conda install parsimonious
```

It is possible to list all of the versions of `parsimonious` available on your platform with:

```
conda search parsimonious --channel nsls2forge
```




Updating parsimonious-feedstock
===============================

If you would like to improve the parsimonious recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/parsimonious-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


