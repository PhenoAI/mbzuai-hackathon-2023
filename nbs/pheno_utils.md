pheno-utils
================

A pip-installable python library for Dataloader and analysis tools.

[See full documentation](https://hrossman.github.io/pheno-utils/)


## Install

``` sh
pip install pheno_utils
```

## Features: Data Loaders

- [PhenoLoader / DataLoader](https://hrossman.github.io/pheno-utils/data_loader.html)
    - Full access to data fields in a specific dataset
    - Access to tabular features
    - Access to raw data (images, time series, genetic variants)
    - Access to field metadata
- [MetaLoader](https://hrossman.github.io/pheno-utils/meta_loader.html)
    - Get an overview of all datasets and search throughout datasets
    - Load tabular features from multiple datasets
    - Load paths to raw data from multiple datasets
- [load_subset](https://hrossman.github.io/pheno-utils/subset_loader.html)
    - Helper function to get train / test data using PhenoLoader / MetaLoader

## How to use

Examples:

``` python
from pheno_utils import PhenoLoader

dl = PhenoLoader("fundus")
```

``` python
from pheno_utils import MetaLoader

ml = MetaLoader()
```
