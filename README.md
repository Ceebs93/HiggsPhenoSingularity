# HiggsPhenoSingularity
The repo for the singularity container that runs packages assocated with higgs phenominology.
## Aim
To run the packages found in 
https://github.com/HenryDayHall/higgsPhenoPackages
## Instructions
Make sure that singularity is installed;
```
sudo apt install singularity-container
```
download this container
```
git clone https://github.com/HenryDayHall/HiggsPhenoSingularity.git
cd HiggsPhenoSingularity
```
build the container
```
sudo singularity build higgsPheno.sif higgsPheno.def
```
run the container
```
singularity run --containall higgsPheno.sif
```


