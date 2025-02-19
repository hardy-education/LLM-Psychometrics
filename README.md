# LLM-Psychometrics Project

# All that Glitters: Approaches to Evaluations with Unreliable Model and Human Annotations

This repository contains the code, data, and supplementary materials for the paper titled "All that Glitters: Approaches to Evaluations with Unreliable Model and Human Annotations" by Michael Hardy. The paper addresses the challenges of using human-mediated labels, which often contain errors, in evaluating models. It highlights how these errors can affect metrics related to accuracy, bias, fairness, and usefulness.

## Table of Contents

- [Introduction](#introduction)
- [Paper Summary](#paper-summary)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Evaluating the quality of classroom teaching using human labels, GPT model ratings, and transformer encoder model annotations is a complex task. This study explores whether such tasks can be automated using Large Language Models (LLMs) and introduces novel evaluation methods across six dimensions: Concordance, Confidence, Validity, Bias, Fairness, and Helpfulness.

## Paper Summary

The study reveals that standard metrics can mask the true quality of labels and models, uncovering issues like spurious correlations and racial biases. It also examines the impact of using models in a human-in-the-loop context and identifies areas where LLMs could potentially improve human ratings of classroom instruction.

- [View PDF](https://arxiv.org/pdf/2411.15634)
- [HTML (experimental)](https://arxiv.org/html/2411.15634v1)
- [DOI: 10.48550/arXiv.2411.15634](https://doi.org/10.48550/arXiv.2411.15634)

## Data

The dataset used in this study includes human annotations, GPT model ratings, and transformer encoder model annotations. The transformer encoder data is available in the `data` directory of this repository.

For detailed instructions on how to use the code, refer to the `README` files in the respective subdirectories.

## Results

The results of the psychometric models from the first section are documented in the `results` directory. This includes detailed analyses of the Concordance, Confidence, Validity, Bias, Fairness, and Helpfulness of the annotations and models.

## Contributing

We welcome contributions to this project. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

For any questions or issues, please open an issue in this repository or contact the author directly.

---

**Author:** Michael Hardy  
**Contact:** [Author's Profile](https://arxiv.org/search/cs?searchtype=author&query=Hardy,+M)

---
