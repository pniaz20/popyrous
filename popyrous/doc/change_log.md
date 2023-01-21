# Change log

## 0

### 0.0

#### 0.0.0

Package created

#### 0.0.1

Added `popyrous.timeseries.experiments.generate_cell_array` and edited the README file.

#### 0.0.2

- Added `popyrous.timeseries.cwt`
- Corrected `popyrous.timeseries.datasets.TabularDataset` such that it no longer supports `in_features` and `out_features` at all.
- Rewrote `popyrous.timeseries.cwt` to have better code, more efficient calculations, and better testing capabilities.
- Updated README according to above changes.

#### 0.0.3

- Modified `popyrous.timeseries.datasets.TabularDataset` such that `powers_of_two` and `dtype` are now constructor arguments rather than class attributes.

#### 0.0.4

- Corrected `popyrous.timeseries.datasets.make_unsqueezed_dataset` such that it no longer tried to input `in_features` and `out_features` to `TabularDataset`.

#### 0.0.5

- Created `popyrous.ml.confusion_matrix.py` for pretty plotting confusion matrix.
- Edited ERADME to give credit to the creator.

#### 0.0.6

- Added `seaborn` to package dependencies due to the previous update.
