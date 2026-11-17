| Rank | Model | Family | RMSE (°C) | MAE (°C) | NRMSE (%) | MASE | R² | Skill vs SN-24 (%) | vs best (DM, 5%) |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Ens-Top3-Mean | Ensemble | 0.6130 | 0.4106 | 7.94 | 0.174 | 0.968 | 72.6 | best |
| 2 | Ens-Top5-InvMSE | Ensemble | 0.6140 | 0.4116 | 7.95 | 0.174 | 0.968 | 72.5 | n.s. |
| 3 | TiRex | Foundation | 0.6224 | 0.4182 | 8.06 | 0.177 | 0.967 | 72.2 | sig. worse |
| 4 | Chronos-2 | Foundation | 0.6235 | 0.4214 | 8.08 | 0.179 | 0.967 | 72.1 | sig. worse |
| 5 | Informer | Transformer | 0.6256 | 0.4266 | 8.10 | 0.181 | 0.967 | 72.0 | sig. worse |
| 6 | TimesFM-2.5 | Foundation | 0.6282 | 0.4223 | 8.14 | 0.179 | 0.967 | 71.9 | sig. worse |
| 7 | Transformer | Transformer | 0.6304 | 0.4333 | 8.16 | 0.184 | 0.967 | 71.8 | sig. worse |
| 8 | TCN | Deep learning | 0.6307 | 0.4310 | 8.17 | 0.183 | 0.967 | 71.8 | sig. worse |
| 9 | N-BEATS | Deep learning | 0.6329 | 0.4304 | 8.20 | 0.182 | 0.966 | 71.7 | sig. worse |
| 10 | DLinear | Transformer | 0.6330 | 0.4343 | 8.20 | 0.184 | 0.966 | 71.7 | sig. worse |
| 11 | iTransformer | Transformer | 0.6330 | 0.4337 | 8.20 | 0.184 | 0.966 | 71.7 | sig. worse |
| 12 | Ridge | Baseline | 0.6377 | 0.4410 | 8.26 | 0.187 | 0.966 | 71.5 | sig. worse |
| 13 | N-HiTS | Deep learning | 0.6424 | 0.4401 | 8.32 | 0.186 | 0.965 | 71.3 | sig. worse |
| 14 | TimesNet | Transformer | 0.6436 | 0.4445 | 8.34 | 0.188 | 0.965 | 71.2 | sig. worse |
| 15 | PatchTST | Transformer | 0.6466 | 0.4492 | 8.37 | 0.190 | 0.965 | 71.1 | sig. worse |
| 16 | TSMixer | Transformer | 0.6476 | 0.4475 | 8.39 | 0.190 | 0.965 | 71.0 | sig. worse |
| 17 | GRU | Deep learning | 0.6487 | 0.4479 | 8.40 | 0.190 | 0.965 | 71.0 | sig. worse |
| 18 | TFT | Transformer | 0.6493 | 0.4505 | 8.41 | 0.191 | 0.964 | 71.0 | sig. worse |
| 19 | Chronos-Bolt-small | Foundation | 0.6525 | 0.4437 | 8.45 | 0.188 | 0.964 | 70.8 | sig. worse |
| 20 | LSTM | Deep learning | 0.6534 | 0.4500 | 8.46 | 0.191 | 0.964 | 70.8 | sig. worse |
| 21 | Persistence | Baseline | 0.6542 | 0.4481 | 8.47 | 0.190 | 0.964 | 70.7 | sig. worse |
| 22 | Chronos-Bolt-base | Foundation | 0.6544 | 0.4479 | 8.48 | 0.190 | 0.964 | 70.7 | sig. worse |
| 23 | CVAE | Generative | 0.6549 | 0.4492 | 8.48 | 0.190 | 0.964 | 70.7 | sig. worse |
| 24 | Autoformer | Transformer | 0.6571 | 0.4610 | 8.51 | 0.195 | 0.964 | 70.6 | sig. worse |
| 25 | ExtraTrees | Tree/ML | 0.6593 | 0.4526 | 8.54 | 0.192 | 0.963 | 70.5 | sig. worse |
| 26 | RandomForest | Tree/ML | 0.6630 | 0.4622 | 8.59 | 0.196 | 0.963 | 70.4 | sig. worse |
| 27 | BiLSTM | Deep learning | 0.6642 | 0.4634 | 8.60 | 0.196 | 0.963 | 70.3 | sig. worse |
| 28 | Prophet-Anchored | Baseline | 0.6764 | 0.4787 | 8.76 | 0.203 | 0.961 | 69.8 | sig. worse |
| 29 | CNN-LSTM | Deep learning | 0.6862 | 0.4862 | 8.89 | 0.206 | 0.960 | 69.3 | sig. worse |
| 30 | LightGBM | Tree/ML | 0.7055 | 0.5108 | 9.14 | 0.216 | 0.958 | 68.5 | sig. worse |
| 31 | XGBoost | Tree/ML | 0.7233 | 0.5224 | 9.37 | 0.221 | 0.956 | 67.7 | sig. worse |
| 32 | SeasonalNaive-24 | Baseline | 2.2365 | 1.7138 | 28.97 | 0.726 | 0.579 | 0.0 | sig. worse |
| 33 | SeasonalNaive-168 | Baseline | 3.7668 | 2.8824 | 48.78 | 1.221 | -0.195 | -68.4 | sig. worse |
| 34 | Prophet | Baseline | 4.2709 | 3.4828 | 55.31 | 1.475 | -0.536 | -91.0 | sig. worse |