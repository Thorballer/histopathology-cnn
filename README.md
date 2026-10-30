# Lung and colon histopathology CNN

An early TensorFlow image-classification experiment on lung/colon histopathology images.

## Notebooks

- [cnn-skin-cancer.ipynb](notebooks/cnn-skin-cancer.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/cnn-skin-cancer)

Despite its original filename, `cnn-skin-cancer` uses lung/colon histopathology images. This is an educational classifier, not a diagnostic tool; dataset splitting and leakage need review before reporting performance.

## Running

Open the original Kaggle notebook, attach its referenced data/models, choose the hardware expected by its setup cells, and run cells in order. Review install, login, and file-writing cells first.

For local use, install `requirements.txt` and adapt `/kaggle/input` paths. Dependencies are inferred from imports, not a tested lockfile; older APIs may need adjustment.

### Referenced Kaggle datasets

- [andrewmvd/lung-and-colon-cancer-histopathological-images](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)

## Status and source

These exports have no saved execution outputs. Training was not rerun, so this archive reports no benchmark scores.

Daniel Goldberg's Kaggle notebooks are preserved with source links and hashes in [PROVENANCE.json](PROVENANCE.json). Documentation was added for this archive.

Original comments, credits, and tutorial links are retained. Datasets and dependencies have their own licenses; no new blanket license is assigned.
