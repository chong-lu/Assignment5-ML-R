conda env create -f environment.yml
conda activate ml-r
R -e "IRkernel::installspec(name = 'ml-r', displayname = 'R (ml-r)')"
