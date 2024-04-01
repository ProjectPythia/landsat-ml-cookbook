![Landsat 8](./notebooks/images/nasa_landsat8.jpg "Landsat 8")

# Landsat ML Cookbook

[![nightly-build](https://github.com/ProjectPythia/landsat-ml-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/landsat-ml-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.projectpythia.org/badge_logo.svg)](http://binder.projectpythia.org/v2/gh/ProjectPythia/landsat-ml-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/563445694.svg)](https://zenodo.org/badge/latestdoi/563445694)

This Project Pythia Cookbook covers the essential materials for working with Landsat data in the context of machine learning workflows.

## Motivation

Once you complete this cookbook, you will have the skills to access, resample, regrid, reshape, and rescale satellite data, as well as the foundation for applying machine learning to it. You will also learn how to interactively visualize your data at every step in the process.

## Authors

[Demetris Roumis](https://github.com/droumis)

### Contributors

<a href="https://github.com/ProjectPythia/landsat-ml-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/landsat-ml-cookbook" />
</a>


This cookbook was initially inspired by the [EarthML](https://github.com/pyviz-topics/EarthML) . See a list of the EarthML contributors [here:](https://github.com/pyviz-topics/EarthML/graphs/contributors)
<a href="https://github.com/pyviz-topics/EarthML/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=pyviz-topics/EarthML" />
</a>

## Structure
This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."

### Foundations
The foundational content includes:
- Start Here - Introduction to Landsat data
- Data Ingestion - Planetary Computer - Demonstrating a method for loading and accessing Landsat data from Microsoft's platform
- Data Ingestion - Intake - Demonstrating approaches for data access using Intake
- Preprocessing - Regrid - Demonstrating common preprocessing approaches such as regridding

### Example Workflows
Example workflows include:
- Spectral Clustering - Demonstrating a machine learning approach to cluster pixels of satellite data and comparing cluster results across time

## Running the Notebooks
You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
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

1. Clone the Landsat ML Cookbook repository:

   ```bash
    git clone https://github.com/ProjectPythia/landsat-ml-cookbook.git
    ```  
1. Move into the `landsat-ml-cookbook` directory
    ```bash
    cd landsat-ml-cookbook
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate landsat-ml-cookbook
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
