# Yeet_Brain
CalgaryHacks2020

## Packages involved
numpy 

OpenBCI_python or pyOpenBCI

Jupyter 

Matplotlib 



### Install Env
conda env create -f environment.yml

### Export Env
conda env export > environment_droplet.yml

### Misc Conda Command

#### list all the conda environment available
conda info --envs  
#### Create new environment named as `envname`
conda create --name envname
#### Remove environment and its dependencies
conda remove --name envname --all
#### Clone an existing environment
conda create --name clone_envname --clone envname

## Base Resources

### Plotting OpenBCI

https://github.com/andreaortuno/Plotting_OpenBCI_Cyton_Data_live

### P300 for muse

https://github.com/NeuroTechX/eeg-notebooks/blob/master/notebooks/P300.ipynb

### Offical OpenBCI Links

#### Cyton Board Programming Tutorial
https://docs.openbci.com/docs/02Cyton/CytonProgram

#### Cyton Board General OVerview
https://docs.openbci.com/docs/02Cyton/CytonLanding

#### Triggering to External Triggers
https://docs.openbci.com/docs/02Cyton/CytonExternal



