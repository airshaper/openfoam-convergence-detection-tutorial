# OpenFoam convergence detection tutorial

## How to run convergence detection tutorial

Source coude is locatated at the link below:

[OpenFoam Convergence Detection Repository](https://github.com/airshaper/openfoam-convergence-detection)

1. Install OpenFoam

```shell
# Add the repository
curl https://dl.openfoam.com/add-debian-repo.sh | sudo bash

# Install openfoam-default (https://develop.openfoam.com/Development/openfoam/-/wikis/precompiled)
# package which includes source files so the functionObject can be compiled
sudo apt-get install openfoam2206-default

```

2. Clone this repository

```shell
git clone https://github.com/airshaper/openfoam-convergence-detection-tutorial.git
```

3. Adjust number of cores in `/system/decomposeParDict`

4. Execute

```shell
./Allrun
```
