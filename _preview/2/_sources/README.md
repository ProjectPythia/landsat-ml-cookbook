<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Landsat ML Cookbook

TODO update badge links transfer to pythia

[![nightly-build](https://github.com/ProjectPythiaCookbooks/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythiaCookbooks/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/ProjectPythiaCookbooks/cookbook-template/main?labpath=notebooks)

This Project Pythia Cookbook covers working with Landsat images in the context of machine learning workflows.

## Motivation

This cookbook provides the essential materials to learning how to work with satellite data using Python. 

Once you complete this cookbook, you will have the  skills to access, resample, regrid, reshape, and rescale satellite data, as well as the foundation for applying machine learning to it. You will also learn how to interactively visualize your data at every step in the process.

## Authors

[Demetris Roumis](https://github.com/droumis)

### Contributors
TODO after transfer to Pythia

## Structure
This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."

### Foundations
The foundational content includes:
- Data Ingestion - Demonstrating common methods for loading and accessing satellite data
- Preprocessing - Demonstrating different preprocessing approaches that for satellite data

### Example Workflows
Example workflows include:
- Spectral Clustering - Demonstrating a machine learning approach to cluster pixels of satellite data and comparing cluster results across time.

## Running the Notebooks
You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)   

1. Clone the Landsat ML Cookbook repository:

   ```bash
    git clone (TODO after transfer)
    ```  
1. Move into the `hv-landsat-cookbook` directory
    ```bash
    cd hv-landsat-cookbook
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate hv-landsat-cookbook
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
