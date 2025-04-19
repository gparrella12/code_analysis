# Evaluating Open-Source Code-LLMs for Vulnerability Detection Under Realistic Conditions

This repository contains the dataset associated with the paper "Evaluating Open-Source Code-LLMs for Vulnerability Detection Under Realistic Conditions".

The dataset is provided in the file `mvfsc_test_set.xlsx`. This file includes the following columns:

*   `index`: A numerical index for each entry.
*   `hash`: The hash of the code snippet.
*   `vul`: A binary indicator where `0` means the code is non-vulnerable and `1` means it is vulnerable.
*   `cwe`: The Common Weakness Enumeration (CWE) identifier associated with the vulnerability (if applicable).
*   `project`: The original project from which the code snippet was sourced.
*   `reference`: A reference to the specific origin within the project (e.g., commit hash, file path).
*   `code`: The source code snippet itself.

The `analysis.ipynb` notebook provides a simple example of how to load and read the dataset.


## Citation

If you use this dataset or find our work useful, please cite the following paper:



## LICENSE
The content of this repository is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.
