**Ablation with paired significance tests (%)**

| Configuration          | Hier. F1     | Δ vs full   | p (paired t)   | Invalid paths   | Accuracy L1   |
|:-----------------------|:-------------|:------------|:---------------|:----------------|:--------------|
| Proposed (full)        | 67.79 ± 0.74 | —           | —              | 0.00 ± 0.00     | 84.84 ± 0.85  |
| Proposed − consistency | 63.80 ± 0.88 | +3.99       | 3.4e-06        | 25.80 ± 0.71    | 83.38 ± 0.98  |
| Proposed − discovery   | 67.80 ± 0.72 | -0.01       | 0.492          | 0.00 ± 0.00     | 84.88 ± 0.82  |
| Proposed − calibration | 67.79 ± 0.74 | +0.00       | —              | 0.00 ± 0.00     | 84.84 ± 0.85  |
