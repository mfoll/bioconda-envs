# Bioconda environments.

See `.yml` files for the content of each environment. 

To create the environment, for example `ngs_align`, use:
```
conda env create -f ngs_align.yml 
```

To activate this environment, use:
```
source activate ngs_align
```

To deactivate an active environment, use:
```
source deactivate
```

To remove an environment, use:
```
conda env remove -n ngs_align
```

To see a list of all of your environments, use:
```
conda env list
```

To see a list of all packages installed in a specific environment, use:
```
conda list -n ngs_align
```
