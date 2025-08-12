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

```bibtex
@InProceedings{10.1007/978-3-032-00644-8_8,
  author="Carletti, Vincenzo
  and Foggia, Pasquale
  and Mazzocca, Carlo
  and Parrella, Giuseppe
  and Vento, Mario",
  editor="Skopik, Florian
  and Naessens, Vincent
  and De Sutter, Bjorn",
  title="Evaluating Large Language Models for Vulnerability Detection Under Realistic Conditions",
  booktitle="Availability, Reliability and Security",
  year="2025",
  publisher="Springer Nature Switzerland",
  address="Cham",
  pages="135--152",
  abstract="Vulnerability Detection (VD) in source code is a critical task for ensuring the security of software systems, particularly in C/C++ languages, which are extensively adopted in safety-critical applications. The recent widespread adoption of Large Language Models (LLMs) for software engineering tasks has led to specialized open-source Code-LLMs, tailored to handle programming languages and code-specific challenges. Although these models have achieved promising results for VD through prompt engineering and fine-tuning strategies, existing studies often evaluate them in unrealistic settings, where test data comes from a similar distribution of training data. In this work, we present a comprehensive evaluation of open-source Code-LLMs for VD in C/C++ code, employing both prompt engineering and fine-tuning approaches. We introduce a novel benchmark dataset composed exclusively of functions extracted from real-world, production-level open-source projects, with the aim to conduct a more realistic analysis. Our results highlight the limitations of current Code-LLMs for VD when evaluated under a realistic setup, emphasizing the need for more robust and generalizable solutions for secure software development.",
  isbn="978-3-032-00644-8"
}
```


## LICENSE
The content of this repository is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.
