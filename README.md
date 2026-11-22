# Lab 3 - Digital filter design: FIR, IIR and adaptive LMS (variant 7)

Noise reduction in a noisy 5 Hz sine (`fs = 1000 Hz`, `N = 1000`, noise `sigma = 0.5`).

Parameters: FIR `b = {1, -1, 0.5}`; IIR `b = {0.3, 0.4}`, `a = {1, -0.5, 0.2}`; LMS `mu = 0.05`, `M = 4`.

## Files

| File | Description |
|------|-------------|
| `lab3_filters_variant7.ipynb` | Notebook with the code |
| `lab3_report_variant7.pdf` | Report |
| `fig_fir.png`, `fig_iir.png`, `fig_lms.png` | Filter outputs |
| `fig_freqresp.png` | Frequency responses |
| `fig_lms_conv.png` | LMS convergence |
