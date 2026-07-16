# Significance-Based-Adaptive-Divisive-Clustering
## Dataset Description

The datasets used in this study are provided in the `Datasets` folder, which contains both **synthetic datasets** and **real-world datasets**.

The synthetic datasets include artificially generated datasets and publicly available clustering benchmark datasets. The real-world datasets are mainly collected from public repositories, including:

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Clustering Basic Benchmark (SIPU)](https://cs.uef.fi/sipu/datasets/)

For consistent data loading and experimental evaluation, all datasets have been converted into `.txt` format. Each row represents one sample, while the columns contain the feature values and the corresponding ground-truth cluster label.

The position of the ground-truth label is indicated by the dataset filename:

- If the filename ends with `_0`, the **first column** contains the ground-truth label.
- Otherwise, the **last column** contains the ground-truth label.
