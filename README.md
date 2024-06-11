# Anomaly Detection Tutorial

This repository contains materials for a hands-on tutorial on Anomaly Detection in Time Series. The tutorial includes interactive live-coding sessions in Jupyter notebooks, using Python and various anomaly detection algorithms from the TSB-UAD Benchmark.

## Important ressources

- TSB-UAD ([github](https://github.com/TheDatumOrg/TSB-UAD)): labeled time seires anomaly detection Datasets and methods
- TSB-kit ([github](https://github.com/boniolp/tsb-kit),[doc](https://tsb-kit.readthedocs.io/en/latest/)): Time seires anomly detection library supporting TSB-UAD
- MSAD ([github](https://github.com/boniolp/MSAD)): Model selection for time series anoamly detection
- ADecimo ([github](https://github.com/boniolp/ADecimo), [streamlit](https://adecimots.streamlit.app/)): Tool for exploring and comparing model selection for time series anoamly detection

## Getting Started

To get started with the tutorial, follow the instructions below:

### 1. Clone the Repository
First, clone the repository to your local machine:
```sh
git clone https://github.com/sylligardos/anomaly-detection-tutorial.git
cd anomaly-detection-tutorial
```

### 2. Download the Dataset
Download the ‘Public’ dataset from the TSB-UAD benchmark:
1. Visit [github.com/TheDatumOrg/TSB-UAD](https://github.com/TheDatumOrg/TSB-UAD).
2. Download the dataset from [this link](https://www.thedatum.org/datasets/TSB-UAD-Public.zip).
3. Unzip the dataset.
4. Move the ‘TSB-UAD-Public’ directory into the `anomaly-detection-tutorial/data/` directory.

### 3. Set Up the Conda Environment
Make sure you have Conda installed, then create and activate the environment:
```sh
conda create --name tutorial python=3.8.13
conda activate tutorial
pip install tsb-kit
pip install jupyter
```

### 4. Open the Tutorial Notebook
Start the Jupyter Notebook server and open the tutorial notebook:
```sh
jupyter notebook
```
In the Jupyter Notebook interface, open the `notebooks/tutorial_paris_2024.ipynb` notebook.

## Usage

The notebooks provided in this repository guide you through various anomaly detection techniques and their applications in time series. Follow along with the instructions in each notebook to learn and implement different methods.
