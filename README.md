# Outlier Detection using MISC-OD

The `MISC-OD` (Mutual Information and Reduced Spectral Clustering - Outlier Detection) algorithm was evaluated in comparison to the Local Outlier Factor (LOF) and Isolation Forest methods for novelty detection using a version of the `Wisconsin Breast Cancer (Diagnostics) dataset`.

For detailed insights into the methodology, please refer to the following reference: [*A Novel Unsupervised Outlier Detection Algorithm Based on Mutual Information and Reduced Spectral Clustering*](https://www.mdpi.com/2079-9292/12/23)

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Installation

To install this project, follow these steps:

```bash
conda env create -f environment.yml -n custom_env_name
```

This command will create a new Conda environment that includes the dependencies needed for the project.

## Usage

To use this project, follow these steps:

```bash
conda activate <env_name>
jupyter notebook
```

Replace `<env_name>` with the name of the Conda environment specified above. This will activate the environment and start Jupyter Notebook, where you can open and run the notebook file.

## Contributors

The following individuals have contributed to this project:

- Ian CoKehyeng
- Rex Gregor Laylo
