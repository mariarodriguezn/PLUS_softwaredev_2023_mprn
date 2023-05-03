# PLUS_softwaredev_2023_mprn
Software Development Course

## Assignment 1:
Candela Pelliza, Felipe Camacho and Elena Nafieva contributed to my repository

## Assignment 2:
Modified the environment "software_dev_v1.yml" using Anaconda Prompt by:
* Updating all the packages: `conda update`
* Installing Pydeck. Noticed that it is faster if the channel is explicitly named: `conda install -c conda-forge pydeck`
* Uninstalling Folium: `conda remove folium`
* Exporting the modified environment: `conda env export -n software_dev_v1>software_dev_v1_mod.yml`

For the environment "software_dev_v2.yml", the environment could not be recreated even if it is OS generic. Possibly, as it does not specify the versions of the packages or dependencies, it can lead to an unsolvable environment. The OS may not be able to resolve the environment because it cannot determine the appropriate versions of the packages to install.
