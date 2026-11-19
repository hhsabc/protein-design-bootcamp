# protein-design-bootcamp

## Project Overview
This is my learning record for AI-driven protein design. I am an undergraduate student exploring computational biology. 

## Pipeline & Milestones
- [x] Successfully configured local WSL2 + Miniconda environment.
- [x] Cloned and installed ProteinMPNN.
- [x] Ran local CPU inference on a test natural PDB structure (1BC8) and generated novel sequences.
- [x] **Successfully ran RFdiffusion on AutoDL cloud GPU to generate a de novo 80-residue backbone.**
- [x] **Designed novel sequences for the de novo backbone using local ProteinMPNN.**
- [x] **Validated the designed sequences using HelixFold (AlphaFold). The predicted structure retains the core alpha-helical topology.**
 - [x] **Wrote a Python script (Biopython) to superimpose structures (RMSD = 2.69 Å).**

## Results

### 1. Test Run (Natural Protein)
- [Natural structure (1BC8)](./1BC8.pdb)
- [Designed sequences for 1BC8](./1BC8_designed_sequences.fa)

### 2. De Novo Design (AI Generated)
- [Original de novo backbone](./my_80_residue_0.pdb)
- [Designed sequences for the backbone](./my_80_residue_0.fa)
- [Predicted structure](./predicted_structure.pdb)

### 3. Code & Scripts
- [Validation Screenshot (Superposition)](./superposition_validation.png)
- [Python Superposition Script](./superpose.py)

## Next Steps
- [ ] Attempt motif scaffolding using RFdiffusion (e.g., RSV-F 163-181).
- [ ] Learn more about protein folding biophysics.
