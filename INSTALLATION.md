1. Install [Anaconda](https://www.continuum.io/downloads)
2. Type the following into a terminal. This creates a new environment with a fresh version of python3 and our packages.
```
conda env create -f environment.yml
```
3. Then to enter this environment, type `source activate quant` to activate your environemnt. Your command line should be prefixed by `(quant)` and look something like this.
```
(quant) bash-3.2$
```
Do this before you start working.


Note:
`conda env export > environment.yml` to export your environment.
