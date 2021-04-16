# Getting Started with Dask

This repository contains the material for **Talk Python Training course** on Getting Started with Dask.

In this **free** course, we will get you up to speed with Dask and show you how to easily convert pandas workloads to blazing Dask clusters (locally across cores or scaled-out across cloud servers).

Learn more and take the course at: [training.talkpython.fm](https://training.talkpython.fm/courses/introduction-to-scaling-python-and-pandas-with-dask)

## Prerequisites

- Python
- pandas
- JupyterLab
- conda
- terminal

## Setup

You get up and running in two ways:

### Launch Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/coiled/talkpython-getting-started-with-dask/master?urlpath=lab/tree/00-setup.ipynb)

The binder project allows you to open Jupyter notebooks in this repository in an online executable environment. Click on the "launch binder" link in your browser window to get started. It might take a few minutes to start.

*Note: Binder notebooks timeout if inactive for more than 10 mins.*

### Local setup (recommended)

* [Fork this repository](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)

* Clone your forked repository:

```git clone http://github.com/<username>/talkpython-getting-started-with-dask```

* From root directory:

```cd talkpython-getting-started-with-dask```

create a new conda environment:

```conda env create -f environment.yml```

* Activate the conda environment:

``` conda activate talkpython-dask```

* Start JupyterLab

```jupyter lab```
