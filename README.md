# DSCI 552 - Homework 2

**Name:** Huang Chihwei
**USC ID:** 9265220160

## Directory structure

```
.
├── README.md
├── requirements.txt
├── data
│   └── CCPP
│       ├── Folds5x2_pp.xlsx
│       ├── Folds5x2_pp.ods
│       └── Readme.txt
└── notebook
    └── Huang_Chihwei_HW2.ipynb
```

## Setup

A virtual environment is used to manage dependencies.

```
py -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Running

Open `notebook/Huang_Chihwei_HW2.ipynb` in Jupyter and run all cells
(Cell → Run All). The notebook loads the data with a relative path
(`../data/CCPP/Folds5x2_pp.xlsx`, Sheet1), so it must be run from within the
`notebook/` folder.

## Contents

- Part 1: Combined Cycle Power Plant regression analysis (exploration, simple
  and multiple linear regression, interaction/nonlinear terms, train/test
  comparison, KNN regression).
- Part 2: ISLR 2.4.1 (flexible vs. inflexible methods).
- Part 3: ISLR 2.4.7 (KNN classification by hand).
