# Restraints evaluation using symmetric cyclodextrin-cyclopentanol complex

Here you will find the YAML and the input files to compute the binding affinity of symmetric cyclodextrin-cyplopentanol and asymmetric-cyclopentanol complexes using several types of restraints. We merged all the YAML files in the [host-guest](https://github.com/MobleyLab/yank-restraints/tree/master/host-guest) directory in 3 YAML files.

## Manifest

- [`restraints.yaml`](restraints.yaml): YAML file to compute the binding affinities of symmetric α-cyclodextrin-cyclopentanol and asymmetric α-cyclodextrin-cyclopentanol complexes using harmonic, Boresch style and flat bottom restraints. The experiments with flatbottom restraints and well radius of 1.5, 2.0 and 3.5 nanometers were specified for the symmetric cyclodextrin-cyclopentanol only.
- [`no-restraints.yaml`](no-restraints.yaml): YAML file to compute the binding affinity of symmetric α-cyclodextrin-cyclopentanol and asymmetric α-cyclodextrin-cyclopentanol complexes without using restraints.
- [`auto-restraints.yaml`](auto-restraints.yaml): YAML file to compute the binding affinity of symmetric α-cyclodextrin-cyclopentanol and asymmetric α-cyclodextrin-cyclopentanol complexes with the auto option to automatically select the alchemical path. 
- [`input`](input): subdirectory containing the mol2 files of symmetric α-cyclodextrin asymmetric α-cyclodextrin and cyclopentanol.
