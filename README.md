# PHASE/0 Snippets

This extension for Visual Studio Code adds snippets for PHASE/0, a first-principles electronic structure calculation software.

## Usage

This extension will be enabled for files that meet the following conditions.

- The file which name is "nfinp.data" or "nfinput.data".
- The first line of the file is "!-\*- PHASE0 -\*-" or "!phase0_input".

## Snippets

Every snippet starts with the prefix "ph-".
Type "ph-" to see the choices.
Please select from the items displayed.

| keywords |  function |
| ---- | ---- |
| ph-control | control block |
| ph-accuracy | accuracy block |
| ph-structure | structure block |
| ph-solver | wavefunction_solver block & charge_mixing block |
| ph-opt-atom-coords | structure_evolution block； optimize fractional coordinates |
| ph-opt-lattice | structure_evolution block；optimize lattice |
| ph-epsilon | epsilon block |
| ph-phonon | phonon (gamma point only) |
| ph-postprocess | postprocess block (DOS, workfunction, partial charge density) |
| ph-molecular-dynamics  | structure_evolution block; NVT, NPT |

The following snippet can be used inside the accuracy block.

| keywords |  function |
| ---- | ---- |
| ph-proj | projector |
| ph-plusU | DFT+U |
| ph-vdwdf | vdW-DF |
| ph-hybrid | hybrid functional (HSE06) |
