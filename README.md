# bonding_from_alchemy

## alchemy.tar
Example input for methylamine to generate cube-files with the CPMD code for the subsequent calculation of atomic energies.

Input, log and pseudopotential files for methylamine (./diatomics/CN), the methylradical (./radical_frags/CC) and amino radical (./radical_frags/NN).

## atomic_energies_alchemy.csv
Atomic contributions to the electronic part of the binding energy (Eq. 10)

smiles: smiles string of the compound

Z1: nuclear of binding partner 1

Z2: nuclear of binding partner 2

E_Z1: atomic energy of atom 1

E_Z2: atomic energy of atom 1

E_Z1_H: sum of atomic energies of the hydrogens bonded to atom 1

E_Z2_H: sum of atomic energies of the hydrogens bonded to atom 2

Eb_homo_Z1: atomic binding energy of atom 1 (Eq. 10)

Eb_homo_Z2: atomic binding energy of atom 2 (Eq. 10)

Eb_homo_Z1_H: sum of atomic binding energies of the hydrogens bonded to atom 1 (Eq. 10)

Eb_homo_Z2_H: sum of atomic binding energies of the hydrogens bonded to atom 2 (Eq. 10)

## 
