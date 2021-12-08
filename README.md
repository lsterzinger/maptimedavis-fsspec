# maptimedavis-fsspec
This repo contains interactive notebooks for a workshop/presentation to [MapTime Davis](https://datalab.ucdavis.edu/spatial-sciences/), part of the [UC Davis DataLab](https://datalab.ucdavis.edu/about/)

Links to recorded presentation will be added once available.


## Options for running:

### Web Browser - Binder:
__Note: Pangeo Binder not currently working -- mybinder.org instance too small to run most examples. Recommend you run locally (see below)__
| Name | Link |
|------|------|
| Pangeo (preferred) | [![Binder](https://mybinder.org/badge_logo.svg)](https://binder.pangeo.io/v2/gh/lsterzinger/maptimedavis-fsspec/main) |
| mybinder.org (fallback) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lsterzinger/maptimedavis-fsspec/main)|

### Running locally
If able, the best option to run this notebook is locally, since generating the references can be easily parallelized with Dask. Clone the repo, create and activate the environment (recommend using [miniconda](https://docs.conda.io/en/latest/miniconda.html)), and launch Jupyter Lab. 

_Tip: Use [Mamba](https://github.com/mamba-org/mamba) instead of Conda for faster environment installation

```
git clone https://github.com/lsterzinger/maptimedavis-fsspec
cd maptimedavis-fsspec

conda env create -f binder/environment.yml
conda activate fsspec-reference-maker

jupyter lab
```

