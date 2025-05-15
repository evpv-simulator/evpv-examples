# Addis Ababa Example

This directory contains an example case study for **Addis Ababa**. 
It contains all necessary input data in the `input/` folder. Results are by default stored in the `output/` folder

You can run the simulation using either the **CLI** (basic usage) or a **Python script** (advanced usage). Below are instructions for both methods:

## 1. Running with CLI (`config_example.py`)

This example demonstrates how to run the simulation using a **CLI** approach with a configuration file.
Populate the configuration file as needed or leave by default. 

Open a terminal in the folder containing the `config_example.py` config file and run:
```bash
evpv
```
and then enter the name to the configuration file. 

> :bulb: Make sure to have your terminal opened in this directory. Otherwise, make sure to specify absolute path files (both in the prompt and in the config file).
> :bulb: Also, if you have installed evpv in a conda environment, do not forget to activate the envrionment first.

## 2. Running with Python Script (`python_script_example.py`)

You can directly execute the simulation by running the script.

Open a terminal in the folder containing the `config_example.py` config file and run:
```bash
python python_script_example.py
```