This directory houses original and intermediate datasets.

Original datasets include:
* **`asec_hh_state.csv.gz`**, extracted from IPUMS with state and other fields required to merge to the CPSP SPM microdata.
* **`pfd_amounts.csv`**, extracted from the PFD Wikipedia page.

It also contains intermediate datasets:
* **`spm_state.csv.gz`**, created via **`gen_data.ipynb`**. Merges ASEC with CPSP data to add state.