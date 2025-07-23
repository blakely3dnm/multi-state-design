colabdesign implementation of multi state design with a focus on ligand induced dimerization. WIP. Credit to colabdesign, chatGPT, and all imported libraries

Automated workflow using PDB codes and optional ligand code as the only inputs.
1. RfDiffusion on a momomeric and dimeric input set to infill gaps and match chain lengths
2. Generates a monomer/dimer paired structure using a homologous dimer template
3. Automatically generates contigs for multi-state sequence design using ProteinMPNN, optionally fixing residues within a radius of a ligand in a reference structure.
4. Validates sequences with AlphaFold2 and generates combined scoring metrics for monomeric and dimeric states
