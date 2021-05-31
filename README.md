# Metaspace Examples

## Submit new datasets

Sometimes it is necessary to submit several datasets with the same data.
To facilitate this process, Jupyter notebooks are provided below that use the python-client under the hood.

* [Batch submit json metadata](./Metaspace_batch_submit_json_metadata.ipynb) - metadata is placed in a separate file `metadata.json` inside the directory with `ibd` and `imzML` files
* [Batch submit with inplace metadata](./Metaspace_batch_submit_inplace_metadata.ipynb) - metadata is set inside the notebook

For these notebooks, need to set the next mandatory constants:
* API_KEY - a key to access the Metaspace API
* PATH_TO_DIRECTORY - directory, wich contains batch of imzML and ibd files