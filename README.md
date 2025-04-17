# FSL Playground

In order not to deal with the setup several times and work within WSL for fMRI analysis without breaking the environment as FSL thinks it's the ruler and doesn't seem to have any intention of alignment and adjustment, this repo includes code following the tutorial from [Andy's Book](https://andysbrainbook.readthedocs.io).

It's tested with

```
WSL-Version: 2.4.13.0
Kernelversion: 5.15.167.4-1
WSLg-Version: 1.0.65
```

using Ubuntu 24.04.


```console
podman build -t fsl-entry .

# To init new container
./.fsl-init

# check the name of the new container then run
# TODO: name is fixed but I'll leave it for now
./fsl-run

# you're in the container, work with fMRI!
```
