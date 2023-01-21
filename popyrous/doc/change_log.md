# Change log

## 0.0.0

Package created

## 0.0.1

Added `popyrous.timeseries.experiments.generate_cell_array` and edited the README file.

## 0.0.2

- Added `popyrous.timeseries.cwt`
- Corrected `popyrous.timeseries.datasets.TabularDataset` such that it no longer supports `in_features` and `out_features` at all.
- Rewrote `popyrous.timeseries.cwt` to have better code, more efficient calculations, and better testing capabilities.
- Updated README according to above changes.

## 0.0.3

- Modified `popyrous.timeseries.datasets.TabularDataset` such that `powers_of_two` and `dtype` are now constructor arguments rather than class attributes.
