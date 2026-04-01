# DATA6550 Reproducibility Project

## Project Title
Reproducing a Hybrid Transformer Model for Wind Time Series Prediction

## Selected Paper
**A hybrid deep learning methodology for wind power forecasting based on attention**  
Yıldırım Akbal and Kamil Demirberk Ünlü  
*International Journal of Green Energy* (2024)

## Links
[Paper URL](https://www.tandfonline.com/doi/abs/10.1080/15435075.2024.2399189?casa_token=FqfoKnv8tJ8AAAAA:sHeclrGDErp6QDS8TGTGZinoinhqjGpYWGrpNtFmRtDFRCX_01-XI9dsrj-fPNG32OqfjajueOb9RA) |
[Dataset URL](https://www.kaggle.com/c/global-energy-forecasting-competition-2012-load-forecasting)

## Project Goal
The goal of this project is to reproduce the results of the selected paper, document the reproduction process, analyze the challenges encountered, and discuss the ethical implications of reproducibility in data science.

## Paper Summary
The selected paper proposes a hybrid deep learning architecture for wind power forecasting based on attention mechanisms. The model combines convolutional layers, attention-based components, and recurrent neural networks to capture temporal dependencies in multiple correlated time series. The study focuses on forecasting wind-related sequential data and reports strong predictive performance.

## Dataset
This project uses the **Global Energy Forecasting Competition 2012 – Wind Forecasting** dataset.

Files used in this project include:
- `train.csv`
- `test.csv`
- `benchmark.csv`
- `windforecasts_wf1.csv` to `windforecasts_wf7.csv`

## Repository Structure
- `Code/` – implementation files for each team member
- `Data/` – original and processed data
- `Analysis/` – figures and result summaries
- `Collaboration/` – weekly collaboration summaries
- `Environment/` – environment and dependency files

## Reproduction Tasks
- Study the selected paper and understand its methodology
- Prepare and preprocess the wind forecasting dataset
- Reproduce the hybrid transformer-based implementation
- Compare reproduced results with the original paper
- Document discrepancies, barriers, and implementation issues
- Discuss the ethical and reproducibility implications

## Environment Setup
Install dependencies using:

```bash
pip install -r Environment/requirements.txt
