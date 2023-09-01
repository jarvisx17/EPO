# European Patent Classification
<img src="https://th.bing.com/th/id/OIP.ZvRlZYpPjNhWAEf2dZZZ3AHaEl?w=282&h=180&c=7&r=0&o=5&dpr=2.5&pid=1.7" alt="Hero image for European Patent Relevancy Check Project" width="100%" height="70%">


## Overview

This project focuses on classifying European patent claims and performing citation matching using BERT (Bidirectional Encoder Representations from Transformers). The goal is to automate and enhance the process of determining the relevance of patent claims and identifying relevant citations in the context of European patents.

## Project Description

In the field of intellectual property and patent law, it is crucial to determine whether a patent claim is relevant to the prior art and to identify citations that support or challenge the novelty and uniqueness of a given patent. Manual review of patents and their associated claims can be time-consuming and error-prone. This project leverages natural language processing techniques and BERT, a state-of-the-art language model, to automate and improve this process.

### Key Features

- **Patent Claim Classification**: The project uses BERT for classifying European patent claims into relevant and non-relevant categories. This helps patent examiners and researchers quickly identify which claims are most pertinent to the patent in question.

- **Citation Matching**: BERT is also employed to perform citation matching, allowing the system to identify citations that are closely related to the content of the patent. This can help in assessing the validity and uniqueness of a patent by comparing it to existing prior art.

- **Jupyter Notebook**: The code and implementation details for this project can be found in the Jupyter Notebook provided in this repository. The notebook contains step-by-step explanations, code snippets, and examples of how the classification and citation matching processes are performed.

## Getting Started

To get started with this project and explore the code and implementation details, follow these steps:

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook [european_patent_relavancy_check](https://github.com/jarvisx17/EPO/blob/main/Final-epo-model-training.ipynb) in your preferred Python environment.
3. Follow the instructions and code cells within the notebook to understand how European patent claims are classified and citations are matched.

## Requirements

Make sure you have the following dependencies installed in your Python environment:

- Python 3.x
- Jupyter Notebook
- PyTorch
- Transformers library (Hugging Face Transformers)
- scikit-learn
- pandas
- numpy

You can install these dependencies using pip or conda by running the following command:

```bash
pip install torch transformers scikit-learn pandas numpy
```

## Usage

The Jupyter Notebook provides detailed instructions on how to use the classification and citation matching models. It includes code examples, data preprocessing steps, and explanations to guide you through the process.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to acknowledge the contributions of the open-source community and the developers of the BERT model and Transformers library. Their work has made this project possible.

---

Feel free to explore the Jupyter Notebook to understand the inner workings of the European Patent Relevancy Check project and leverage the power of BERT for patent analysis and classification. If you have any questions or encounter any issues, please don't hesitate to reach out to the project maintainers.
