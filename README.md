# BlueQuant-alpha-tools
BlueQuant alpha tools

# Requirements
+ Python
+ Matplotlib

# PNL Summary
Print summary of a pnl file, only one alpha at a time
```
python3 pnl_summary.py pnl/alpha1
```
The output will be like
```
   START-     END    LONG  SHORT      PNL    TVR    RET     DD  SHARPE
20180101-20181231   500.0  500.0    403.0   48.5   42.6   35.5   0.052
20190101-20191231   500.0  500.0    526.6   53.9   53.9   17.5   0.064
20200101-20201230   500.0  500.0    478.6   53.8   49.4   46.0   0.034
20210101-20211231   500.0  500.0    443.2   49.1   47.2   79.3   0.022
20220101-20221231   500.0  500.0   -512.7   58.4  -53.5   80.1  -0.060
20230101-20231231   470.1  470.1    117.3   57.4   13.3   23.7   0.022
20240101-20240819   500.0  500.0    -92.8   56.0  -15.5   31.9  -0.032

20180101-20240819   495.6  495.6   1363.2   53.7   21.7  135.7   0.018
```

# Plot PNL
Plot pnl chart of alphas, can plot multiple alphas in one graph
```
python3 pnl_plot.py pnl/alpha1 pnl/alpha2 pnl/alpha3
```
The graph is like below
![Figure_1](https://github.com/user-attachments/assets/3450e777-a006-4dbb-a21c-ccd070049dad)
