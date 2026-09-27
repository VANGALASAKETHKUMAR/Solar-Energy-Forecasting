# Model Verification

The completed notebook was executed using the four supplied source CSV files.

## Preprocessing verification

| Measure | Case-study report | Executed notebook |
|---|---:|---:|
| Analytical observations | 6,416 | 6,416 |
| Plant 1 AC-power total | 21,167,150 | 21,167,150 |
| Plant 2 AC-power total | 16,334,026 | 16,334,026.21 |

## Forecasting verification

| Metric | Case-study report | Executed notebook |
|---|---:|---:|
| MAE | 467.41 | 496.35 |
| RMSE | 1208.99 | 1277.63 |
| R² | 0.9693 | 0.9658 |

The preprocessing pipeline reproduces the reported analytical dataset size and plant totals. The executed Random Forest metrics differ from the report values, so the repository preserves the actual reproducible results rather than presenting the report's metrics as if they were reproduced.
