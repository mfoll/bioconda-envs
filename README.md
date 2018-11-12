# Bioconda environments for bioinformatics.

## Installation

Clone the repository to get the environment `.yml` files:
```
git clone https://github.com/mfoll/bioconda-envs.git
```

To create the environments use:
```
cd bioconda-envs
conda env create -f ngs_process.yml 
conda env create -f ngs_qc.yml 
conda env create -f ngs_align.yml 
conda env create -f ngs_call.yml 
```

## Usage

To activate an environment, for example `ngs_align`, use:
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

To update packages in an environment, use:
```
conda update -n ngs_align --all
```

To see a list of all of your environments, use:
```
conda env list
```

To see a list of all packages installed in a specific environment, use:
```
conda list -n ngs_align
```

See also the content of each `.yml` file. 

