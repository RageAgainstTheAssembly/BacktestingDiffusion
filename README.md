# BacktestingDiffusion
Controllable Generation of Realistic Financial Time Series via Diffusion Models

## Datasets

To run the code, you'll need to download the following financial datasets and place them in the `data` folder:

1. **S&P 500 Dataset**
   - Description: Multivariate daily log returns for S&P 500 constituents
   - Download: [S&P 500 Data](https://drive.google.com/file/d/1icdGTknqOXfJKPfbChKjYLYjfG5r8nR3/view?usp=sharing)

2. **MOEX Dataset**
   - Description: Multivariate daily log returns for Moscow Exchange stocks
   - Download: [MOEX Data](https://drive.google.com/file/d/1TbV-1_IYBMwGaK0_peLpuj4d8RcFHEUo/view?usp=sharing)

3. **Forex Dataset**
   - Description: Multivariate daily exchange rates for major currency pairs
   - Download: [Forex Data](https://drive.google.com/file/d/1r-ENCVtztcDaBHdvawLWHFIc3_NJSNPF/view?usp=sharing)

### Data Setup Instructions

1. Create a `data` folder in the root directory of the project if it doesn't exist:
```bash
mkdir data
```

2. Download all datasets from the provided Google Drive links

3. Place the downloaded files directly in the `data` folder without modifying their names

4. Verify that your data folder structure looks like this:
```
data/
├── sp500_returns.csv
├── moex_returns.csv
└── forex.csv
```

