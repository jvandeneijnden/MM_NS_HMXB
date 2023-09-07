# Analysis reproduction repository for "The first mm detection of a neutron star high-mass X-ray binary"

![Stellar wind inferences](Figure1.png?raw=true "Stellar wind inferences")

## Based on Van den Eijnden et al. (2023), MNRAS Letters accepted.
The full paper, included updated versions can be found on https://arxiv.org/abs/2308.06021 (open access).

This reproduction repository contains a Jupyter notebook to reproduce the images and analysis in the above paper. In order to run the notebook, check the software requirements below, clone the repository, and run through each cell. The motivations for the analysis are included to limited extend, but we refer to the full paper for all details.

The notebook includes the calibrated .UVT data files from the NOEMA telescope per target and sub band (LSB and USB). Dedicated NOEMA software (Gildas mapping, see https://www.iram.fr/IRAMFR/GILDAS/) is required to open and manipulate these files.

Please get in touch via email (jakob.van-den-eijnden [at] warwick.ac.uk) or via github with questions.

If this repository is useful for your own research, in addition to citing the original paper, please consider including a note to this repository as well.

## Software requirements

To reproduce the analysis and figures, the notebook is written in Python 3. Conversion to python 2 should be straightforward but not recommended.

The notebook uses the following packages:

- numpy
- matplotlib
- astropy










