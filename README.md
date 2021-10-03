# maptimedavis-fsspec

## Options for running:

### Web Browser - Google Colab:
* [01-Create_References.ipynb](https://colab.research.google.com/github/lsterzinger/maptimedavis-fsspec/blob/main/01-Create_References.ipynb)
* [02-Plotting.ipynb](https://colab.research.google.com/github/lsterzinger/maptimedavis-fsspec/blob/main/02-Plotting.ipynb)

### Web Browser - Binder:
| Name | Link |
|------|------|
| mybinder.org | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lsterzinger/maptimedavis-fsspec/main)|
| Pangeo | [![Binder](https://mybinder.org/badge_logo.svg)](https://binder.pangeo.io/v2/gh/lsterzinger/maptimedavis-fsspec/main) |

### Running locally
The best option to run this notebook is locally, since generating the references can be easily parallelized with Dask. Clone the repo, create and activate the environment, and launch Jupyter Lab.

```
git clone https://github.com/lsterzinger/maptimedavis-fsspec
cd maptimedavis-fsspec

conda env create -f environment.yml
conda activate fsspec-reference-maker

jupyter lab
```

