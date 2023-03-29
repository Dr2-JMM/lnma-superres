# lnma-superres

[![License BSD-3](https://img.shields.io/pypi/l/lnma-superres.svg?color=green)](https://github.com/Dr2-JMM/lnma-superres/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/lnma-superres.svg?color=green)](https://pypi.org/project/lnma-superres)
[![Python Version](https://img.shields.io/pypi/pyversions/lnma-superres.svg?color=green)](https://python.org)
[![tests](https://github.com/Dr2-JMM/lnma-superres/workflows/tests/badge.svg)](https://github.com/Dr2-JMM/lnma-superres/actions)
[![codecov](https://codecov.io/gh/Dr2-JMM/lnma-superres/branch/main/graph/badge.svg)](https://codecov.io/gh/Dr2-JMM/lnma-superres)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/lnma-superres)](https://napari-hub.org/plugins/lnma-superres)


A plugin for super-resolution microscopy FF-SRM methods.

Open-source implementation of methods for Fluorescence Fluctuation based Super Resolution Microscopy (FF-SRM):

Review: [Alva et al., 2022. “Fluorescence Fluctuation-Based Super-Resolution Microscopy: Basic Concepts for an Easy Start.” Journal of Microscopy, August. https://doi.org/10.1111/jmi.13135](https://onlinelibrary.wiley.com/doi/10.1111/jmi.13135)

MSSR article: [Torres-García, E., Pinto-Cámara, R., Linares, A. et al. Extending resolution within a single imaging frame. Nat Commun 13, 7452 (2022). https://doi.org/10.1038/s41467-022-34693-9](https://doi.org/10.1038/s41467-022-34693-9)

Implemented methods so far:
- MSSR
<!-- - ESI -->

----------------------------------

This [napari] plugin was generated with [Cookiecutter] using [@napari]'s [cookiecutter-napari-plugin] template.

<!--
Don't miss the full getting started guide to set up your new package:
https://github.com/napari/cookiecutter-napari-plugin#getting-started

and review the napari docs for plugin developers:
https://napari.org/stable/plugins/index.html
-->

## Installation
First install napari viewer:

    conda create -y -n napari-env -c conda-forge python=3.9
    conda activate napari-env
    pip install "napari[all]"

For details check: https://napari.org/stable/

<!-- Then, you can install `lnma-superres` napari plugins via [pip]:

    pip install lnma-superres -->



To install latest development version :

    pip install git+https://github.com/Dr2-JMM/lnma-superres.git


## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [BSD-3] license,
"lnma-superres" is free and open source software

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[napari]: https://github.com/napari/napari
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[@napari]: https://github.com/napari
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin

[file an issue]: https://github.com/Dr2-JMM/lnma-superres/issues

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
