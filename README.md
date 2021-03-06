# Mesothelioma Data Visualizations

Visualize mesothelioma mortality in the United States.
[`mesothelioma.ipynb`](mesothelioma.ipynb) creates the following figure:

![mesothelioma mortality by US state](figure/mortality.png)

## Environment

This repository uses [conda](http://conda.pydata.org/docs/) to manage its environment as specified in [`environment.yml`](environment.yml).
Install the environment with:

```sh
conda env create --file=environment.yml
```

Then use `source activate mesothelioma` and `source deactivate` to activate or deactivate the environment.
On windows, use `activate mesothelioma` and `deactivate` instead.

## License

This repository is dedicated to the public domain.
See [`LICENSE.md`](LICENSE.md) for details.
