# Open Chemistry JupyterLab Examples

This repository contains a number of notebooks created using the
[Open Chemistry][openchemistry] projects to create notebooks that can be run
locally and/or within Binder. The binder directory shows what Python 3 modules
are needed, and the JupyterLab extension necessary to make everything work.

These examples, and the APIs shown, are all subject to change. This is an early
technical preview of our work. All code is available under the 3-clause BSD
license, and any data is made available under the CC-BY 4.0 license.

A simple notebook shows you how to load a Chemical JSON file with the output of
an NWChem calculation for the [caffeine molecule][caffeine], that link should
open the notebook in Binder, using the JupyterLab interface. You can also
install the necessary components locally and run everything on your own machine.
The [Avogadro][avogadro] notebook shows you how to load a quantum output file
supported by Avogadro libraries, and translate it to Chemical JSON using the
Python wrapped API.

[openchem]: https://openchemistry.org/
[caffeine]: http://mybinder.org/v2/gh/openchemistry/jupyter-examples/master?urlpath=lab/tree/caffeine.ipynb
[avogadro]: http://mybinder.org/v2/gh/openchemistry/jupyter-examples/master?urlpath=lab/tree/avogadro.ipynb
