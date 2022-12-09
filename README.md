# bonding_from_alchemy

## alchemy.tar
Example input for methylamine to generate cube-files with the CPMD code for the subsequent calculation of atomic energies.

Input, log and pseudopotential files for methylamine (./diatomics/CN), the methylradical (./radical_frags/CC) and amino radical (./radical_frags/NN).

## atomic_energies_alchemy.csv
Atomic contributions to the electronic part of the binding energy (Eq. 10)

smiles: smiles string of the compound

Z1: nuclear charge of binding partner 1

Z2: nuclear charge of binding partner 2

E_Z1: atomic energy of atom 1

E_Z2: atomic energy of atom 1

E_Z1_H: sum of atomic energies of the hydrogens bonded to atom 1

E_Z2_H: sum of atomic energies of the hydrogens bonded to atom 2

Eb_homo_Z1: atomic binding energy of atom 1 (Eq. 10)

Eb_homo_Z2: atomic binding energy of atom 2 (Eq. 10)

Eb_homo_Z1_H: sum of atomic binding energies of the hydrogens bonded to atom 1 (Eq. 10)

Eb_homo_Z2_H: sum of atomic binding energies of the hydrogens bonded to atom 2 (Eq. 10)


## binding_energies_pbe0.csv
Binding energies for single bonded molecules calculated with PBE0/def2-TZVP

smiles: smiles string/heavy atoms

Z1: nuclear charge of binding partner 1

Z2: nuclear charge of binding partner 2

d: distance between binding partner 1 and binding partner 2

energy: total energy in Hartree

bfe: bond formation energy in Hartree

## binding_energies_db_row_[row number].csv
Binding energies for double bonded molecules calculated with PBE0/def2-TZVP in rows 2, 3, 4 of the periodic table

Z1: nuclear charge of binding partner 1

Z2: nuclear charge of binding partner 2

bde_TS: energy difference (in Hartree) between fragments in triplet and molecules in singlet state 

bde_GS: energy difference (in Hartree) between fragments and molecules in their ground state

bde_TT: energy difference (in Hartree) between fragments in triplet and molecules in triplet state 

bde_SS: energy difference (in Hartree) between fragments in singlet and molecules in singlet state 

## optimization_models.ipynb
Code to optimize the paramters in Eq. (2), (12), (18), (25)

Code for the recalibration of the model to double bonds

Code for the recalibration of the model to random data from a uniform distribution




