# waveform_analysis

Follow through this notebook to:

1. Open up the root files containing the digitizer's waveforms.

2. Run through each channel and waveform to find the PMT's pulse information, namely, amplitude, charge and timing. 

3. Generate waveform figures for a given event.

4. Store the pulse information in a ROOT file.

## Cloning the Repository to your Computer

You may either directly download the ```waveform_analysis.ipynb``` to your computer, or, if you have git installed, you may clone this repository by using

```git clone https://github.com/luanviko/waveform_analysis```

on a terminal window. This command will copy the contents of this repository to the directory you currently are.

## Jupyter start-up

After installing the dependencies of this project and/or sourcing the correct python environment, open a terminal window and run the command

```jupyter notebook```

A new tab on your default browser should open up, showing the base directory in which you ran the command above. 

Navigate to the clone folder and open open 

## Running the Analysis

Follow through the notebook by running each cell with ```Shit+Enter```.


## Dependencies and Environments

This notebook requires the installation of the packages: ```jupyter```, ```matplotlib```, ```numpy```, and ```uproot```.


### Using pip

These steps should work on most linux distros and macOS versions.

Create a new python environment specifically for this project, in the same clone directory. 

```python3 -m venv ./analysis_environment```

Activate this environment:

```source ./analysis_environment/bin/activate```

Install the dependencies of this project in 

```python3 -m pip install jupyter matplotlib numpy uproot```
