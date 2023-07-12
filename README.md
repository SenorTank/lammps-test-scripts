# lammps-test-scripts

A group of test scripts that work with protein 2gb1, mainly giving an introduction to LAMMPS

## Lammps Scripts

The scripts are broken up based on steps that I am performing. First I minimize the model. This step is of course to reduce the high energy states in the lattice network that CHARMMS2LAMMPS script provides. This is given from the `.data` file which then in the minimzation script it will execute two `minimize` functions back to back. I will add later the exacts of the changes that it pushes and the math behind it, but in the mean time it will suffice to say that it is just a short run that just preps the model for NPT runs. The NPT runs follow up by running off the minimized model output and runs it to measure the box lengths and changes in that.

### Minimization Script

Non figuratum est quod hic scribere volo.

### NPT Script

Non figuratum est quod hic scribere volo.

## Future Plans

I am planning to continue to improve these scripts, it is a very small protein so the runs can be relatively short even for a regular non gpu/mpi accelerated run. It may still take a couple hours without the multithreading but it will work well. So not much has to be done to really optimize the runs, it is just the data that I need to collect that might take a while.
