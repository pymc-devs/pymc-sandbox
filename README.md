# PyMC binder sandbox

This repository is used to store the binder environment used to run the
notebooks in https://docs.pymc.io/projects/examples/en/latest/ (hosted
on [this GitHub repo](https://github.com/pymc-devs/pymc-examples))

This freezes the dependencies at the time of each [snapshot]()
to ensure notebooks can always be executed on binder and
accelerate loading the binder kernel for the notebooks.

### Contributors
To update the `requirements.txt` use `pip-compile requirements.in` which will
generate the new `requirements.txt`. You'll need `pip-tools` installed
