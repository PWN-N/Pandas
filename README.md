# Pandas Learning Notebooks

This repository is a set of beginner-oriented Jupyter notebooks for learning the core pieces of the Python pandas library. The examples build small DataFrames and Series directly in the notebooks and demonstrate common data preparation, analysis, and reshaping tasks.

## Repository contents

All learning materials are in the `Pandas/` directory:

| Notebook | Concepts and examples |
| --- | --- |
| `Pandas/1. Series.ipynb` | What a Series is; creating Series from lists, NumPy arrays, and dictionaries; assigning index labels |
| `Pandas/2. Dataframes.ipynb` | Creating DataFrames from dictionaries and lists; selecting columns and rows; adding and dropping columns; selecting subsets; filtering with conditions |
| `Pandas/3. MissingData.ipynb` | Finding missing values with `isna`; counting and checking nulls; dropping rows by null presence or threshold; filling with constants, per-column values, and column means |
| `Pandas/4. MergingJoiningConcatination.ipynb` | Combining data with `merge` (inner, outer, left, and right), `concat` (row-wise and column-wise), and index-based `join` |
| `Pandas/5. GroupByAggregation.ipynb` | Grouping by one or multiple columns; summarizing sales; common statistics and multi-function aggregation with `agg` |
| `Pandas/6. PivotTables.ipynb` | Building pivot tables for sales and units; using rows, columns, and aggregation functions; creating cross-tabulations with `crosstab`; deriving month and quarter columns from dates |
| `Pandas/7. Operations.ipynb` | Inspecting DataFrames with `shape`, `columns`, `info`, and `describe`; arithmetic; applying named and lambda functions to columns |

The examples use small, in-notebook sample datasets (including employees, sales, and missing values), so no external data files are required. The pivot-table notebook generates random sales and unit values; those values can differ between runs.

## Requirements

- Python 3
- Jupyter Notebook
- pandas
- NumPy

Install the requirements:

```bash
python -m pip install jupyter pandas numpy
```

## Run the notebooks

From the repository root, launch Jupyter:

```bash
jupyter notebook
```

Open a notebook in the `Pandas/` directory. Run cells from top to bottom so that each example's variables and DataFrames are defined before they are used. You can edit the sample data and rerun cells to explore how the results change.

## Suggested learning path

Start with Series and DataFrames, then practice filtering and missing-data handling. Continue with combining DataFrames and grouped summaries, and finish with pivot tables and general DataFrame operations.
