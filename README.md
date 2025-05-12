![LOGO](https://github.com/DeepWave-KAUST/FreqSiameseFWI-dev/blob/main/asset/FreqSiamese.jpg)

Reproducible material for **FreqSiameseFWI: A Novel Deep Learning Framework for Multi-Source Full Wave Inversion - Omar M. Saad and Tariq Alkhalifah**

[Click here]() to access the Project Report. Authentication to the _Restricted Area_ filespace is required.

# Project structure
This repository is organized as follows:

* :open_file_folder: **asset**: folder containing logo;
* :open_file_folder: **data**: folder containing Marmousi2 and overthrust models data;
* :open_file_folder: **utils**: set of common function to run FWI;
* :open_file_folder: **Model**: containing FreqSiamese network;
* :open_file_folder: **results**: containing the reconstructed velocity model using FreqSiameseFWI;

## Notebooks
The following notebooks are provided:

- :orange_book: ``FreqSiameseFWI_Marmousi_FWI.ipynb``: the main notebook performing the FreqSiameseFWI for Marmousi model;
- :orange_book: ``FreqSiameseFWI_overethrust_FWI.ipynb``: the main notebook performing the FreqSiameseFWI for overthrust model;
- :orange_book: ``FreqSiameseFWI_Marmousi_MSFWI.ipynb``: the main notebook performing the FreqSiameseFWI for Marmousi model (multi-sources);
- :orange_book: ``FreqSiameseFWI_overethrust_MSFWI.ipynb``: the main notebook performing the FreqSiameseFWI for overthrust model (multi-sources);


## Getting started :space_invader: :robot:
- To ensure the reproducibility of the results, we suggest using the `FWIGAN.yml` file when creating an environment.
- Please install the Deepwave 0.0.8 toolbox version, which is used in this project.
Run:
```
./install_env.sh
```
It will take some time, but if you see the word `Done!` on your terminal you are ready to go. 

Remember to always activate the environment by typing:
```
conda activate FWIGAN
```

**Disclaimer:** All experiments have been carried on a Intel(R) Xeon(R) CPU @ 2.10GHz equipped with a single NVIDIA GEForce RTX 3090 GPU. Different environment 
configurations may be required for different combinations of workstation and GPU.

## Cite us 
DW0060 - Omar M. Saad and Tariq Alkhalifah (2024) FreqSiameseFWI: A Novel Deep Learning Framework for Multi-Source Full Wave Inversion.

