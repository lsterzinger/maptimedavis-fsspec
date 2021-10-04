# maptimedavis-fsspec

## Options for running:

### Web Browser - Binder:
| Name | Link |
|------|------|
| Pangeo (preferred) | [![Binder](https://mybinder.org/badge_logo.svg)](https://binder.pangeo.io/v2/gh/lsterzinger/maptimedavis-fsspec/main) |
| mybinder.org | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lsterzinger/maptimedavis-fsspec/main)|

### Running locally
The best option to run this notebook is locally, since generating the references can be easily parallelized with Dask. Clone the repo, create and activate the environment (recommend using [miniconda](https://docs.conda.io/en/latest/miniconda.html)), and launch Jupyter Lab. 

```
git clone https://github.com/lsterzinger/maptimedavis-fsspec
cd maptimedavis-fsspec

conda env create -f environment.yml
conda activate fsspec-reference-maker

jupyter lab
```

