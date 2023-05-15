# c1-versus-reality
Comparison of C1a and C1b scenarios versus historical emissions.

## Reproduction

First clone the repository. Then create the environment:

```
conda env create -f environment.yml
```
If you want to make nice version-control friendly notebooks, which will remove all output and data upon committing, run

```
nbstripout --install
```

To run, fire up a terminal and do

```
conda activate c1-versus-reality
jupyter notebook
```

then navigate to the `notebooks` directory and run `compare.ipynb`.
