| Rank | Model | Family | RMSE (MW) | MAE (MW) | NRMSE (%) | MASE | R² | Skill vs SN-24 (%) | vs best (DM, 5%) |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Ens-Top5-InvMSE | Ensemble | 55.97 | 42.93 | 1.01 | 0.121 | 0.997 | 88.6 | best |
| 2 | TCN | Deep learning | 56.22 | 43.21 | 1.01 | 0.122 | 0.997 | 88.5 | sig. worse |
| 3 | Ens-Top3-Mean | Ensemble | 56.53 | 43.36 | 1.02 | 0.123 | 0.997 | 88.5 | sig. worse |
| 4 | MLP | Deep learning | 56.58 | 43.26 | 1.02 | 0.122 | 0.997 | 88.5 | sig. worse |
| 5 | CNN-LSTM | Deep learning | 58.06 | 44.44 | 1.05 | 0.126 | 0.997 | 88.2 | sig. worse |
| 6 | BiLSTM | Deep learning | 58.87 | 45.12 | 1.06 | 0.128 | 0.996 | 88.0 | sig. worse |
| 7 | GRU | Deep learning | 58.90 | 45.35 | 1.06 | 0.128 | 0.996 | 88.0 | sig. worse |
| 8 | LSTM | Deep learning | 59.82 | 45.91 | 1.08 | 0.130 | 0.996 | 87.8 | sig. worse |
| 9 | ExtraTrees | Tree/ML | 66.29 | 50.67 | 1.19 | 0.143 | 0.996 | 86.5 | sig. worse |
| 10 | LightGBM | Tree/ML | 68.40 | 52.20 | 1.23 | 0.148 | 0.995 | 86.1 | sig. worse |
| 11 | RandomForest | Tree/ML | 69.36 | 52.54 | 1.25 | 0.149 | 0.995 | 85.9 | sig. worse |
| 12 | XGBoost | Tree/ML | 74.20 | 56.47 | 1.34 | 0.160 | 0.994 | 84.9 | sig. worse |
| 13 | Ridge | Baseline | 88.35 | 67.59 | 1.59 | 0.191 | 0.992 | 82.0 | sig. worse |
| 14 | Prophet-Anchored | Baseline | 139.47 | 110.33 | 2.51 | 0.312 | 0.980 | 71.6 | sig. worse |
| 15 | Persistence | Baseline | 213.89 | 167.61 | 3.86 | 0.474 | 0.954 | 56.4 | sig. worse |
| 16 | SeasonalNaive-24 | Baseline | 490.69 | 368.58 | 8.84 | 1.043 | 0.756 | 0.0 | sig. worse |
| 17 | SeasonalNaive-168 | Baseline | 779.57 | 584.64 | 14.05 | 1.654 | 0.385 | -58.9 | sig. worse |
| 18 | Prophet | Baseline | 812.12 | 679.65 | 14.64 | 1.922 | 0.333 | -65.5 | sig. worse |