# Quantile-Frequency Analysis (QFA) & Spline Quantile Regression (SQR)

Quantile-frequency analysis, or QFA, is a nonlinear spectral analysis method for time-series data  based on quantile periodograms computed from trigonometric quantile regression [1][2][3][8][9]. The QFA method, together with its extension called short-time QFA (STQFA), is able to provide a richer view of time-series data than traditional power spectra and spectrograms.

Spline quantile regression, or SQR, is a method of estimating the coefficients in linear quantile regression as smooth functions of the quantile level by linear and quadratic programming [10][11]. Based on linear and cubic splines, the SQR method provides a global view of the conditional quantile function which extends the isolated view at a specific quantile offered by traditional quantile regression.

## Content

- This repo contains an R package qfa_x.x.tar.gz for download with the associated manual qfa_x.x.pdf. The package is also available at https://cran.r-project.org/ by the name of 'qfa'.

  Install downloaded package in R console: install.packages("path_to_the_downloaded_package_on_your_computer/qfa_x.x.tar.gz", repos = NULL, type = "source")

- This repo contains an R code (qfa_fpca_code.txt) for functional principal component analysis (FPCA) of quantile periodograms, and classification of time series using LDA, QDA, and SVM based on QFA-FPCA features [4].

- This repo contains a Python code (QFA-DL-code.zip) for classification of time series using QFA and STQFA combined with Deep Learning (MLP and CNN) [5][6].

- This repo contains in the data/NDE/ directory the csv files of pre-calculated quantile and traditional spectra used in [6] for classification of the nondestructive evaluation (NDE) signals available at https://www.math.umd.edu/~bnk/DATA/. 
  - quantile periodograms (bond_disbond_qper_for_cnn.zip)
  - short-time quantile periodograms (bond_disbond_stqfa_for_cnn_15x45x29.zip)
  - traditional periodograms (bond_disbond_per_for_cnn.zip)
  - traditional spectrograms (bond_disbond_stft_for_cnn_15x29.zip)
  
- Additional data files are also available in the data/ directory.

## References

The preprints of the following articles can be found in the references/ directory.


[1] T.-H. Li (2008), "Laplace periodogram for time series analysis," Journal of the American Statistical Association, 103:482, 757-768. https://doi.org/10.1198/016214508000000265

[2] T.-H. Li (2012), "Quantile periodograms", Journal of the American Statistical Association, 107:498, 765-776. http://dx.doi.org/10.1080/01621459.2012.682815

[3] T.-H. Li (2014), Time Series with Mixed Spectra, CRC Press. https://doi.org/10.1201/b15154

[4] T.-H. Li (2020), "From zero crossings to quantile-frequency analysis of time series with an application to nondestructive evaluation", Applied Stochastic Models for Business and Industry, 36:6, 1111-1130. https://doi.org/10.1002/asmb.2499

[5] T. Chen, Y. Sun, and T.-H. Li (2021), "A semi-parametric estimation method for the quantile spectrum with an application to earthquake classification using convolutional neural network", Computational Statistics and Data Analysis, 153, 107069. https://doi.org/10.1016/j.csda.2020.107069

[6] T.-H. Li (2023), "Quantile-frequency analysis and deep learning for signal classification," Journal of Nondestructive Evaluation, 42, 40. https://doi.org/10.1007/s10921-023-00952-y

[7] C. Jiménez-Varón, Y. Sun, and T.-H. Li (2024), "A semi-parametric estimation method for quantile coherence with an application to bivariate financial time series clustering," Econometrics and Statistics, https://doi.org/10.1016/j.ecosta.2024.11.002

[8] T.-H. Li (2025), "Quantile Fourier transform, quantile series, and nonparametric estimation of quantile spectra," Communications in Statistics - Simulation and Computation, https://doi.org/10.1080/03610918.2025.2509820

[9] T.-H. Li (2025), "Spline autoregression method for estimation of quantile spectrum," Journal of Computational and Graphical Statistics, https://doi.org/10.1080/10618600.2025.2549452, available at https://www.tandfonline.com/eprint/PK8TCERG83KHH9YJABJ6/full?target=10.1080/10618600.2025.2549452

[10] T.-H. Li and N. Megiddo (2026), "Spline quantile regression," Journal of Statistical Theory and Practice, https://doi.org/10.1007/s42519-026-00545-8

[11] T.-H. Li (2026), "Spline quantile regression with cubic and linear smoothing splines," arXiv:2603.22408, https://doi.org/10.48550/arXiv.2603.22408

## Contact

For further inqueries, please contact Ta-Hsin Li (thl024@outlook.com)

