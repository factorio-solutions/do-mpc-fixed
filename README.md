# Model predictive control python toolbox
This is a fork to have a handy source for remote deployment of projects that use a fixed MHE.

## Building Wheels
For releases, I used `poetry build` command and then uploaded release binaries to the github page. In other projects, I use `poetry add path/to/git/relase/binaries`. E.g.:
```shell
poetry add https://github.com/factorio-solutions/do-mpc-fixed/releases/download/v4.3.5.1/do-mpc-4.3.5.1.tar.gz
```

## Installation instructions
Installation instructions for the original `do-mpc` are given [here](https://www.do-mpc.com/en/latest/installation.html).

## Documentation
Please visit our extensive [documentation](https://www.do-mpc.com), kindly hosted on readthedocs.

## Citing **do-mpc**
If you use **do-mpc** for published work please cite it as:

S. Lucia, A. Tatulea-Codrean, C. Schoppmeyer, and S. Engell. Rapid development of modular and sustainable nonlinear model predictive control solutions. Control Engineering Practice, 60:51-62, 2017

Please remember to properly cite other software that you might be using too if you use **do-mpc** (e.g. CasADi, IPOPT, ...)
