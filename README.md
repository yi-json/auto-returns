# Nonlinear Factor Models in Financial Markets: A Comparative Study of Autoencoders and PCA

This project explores the use of autoencoders as a nonlinear alternative to Principal Component Analysis (PCA) for dimensionality reduction, clustering, and anomaly detection in financial return data. Using historical data from Yahoo Finance and Alpha Vantage, we evaluate how effectively these models extract latent market factors and uncover nonlinear structures.

## 🧠 Core Objectives
- Compare PCA and autoencoders for reconstructing standardized daily returns
- Evaluate performance using R² and Mean Squared Error (MSE)
- Apply K-Means clustering to latent features from both models
- Detect anomalies using both classical statistics (Z-score, IQR) and machine learning (Isolation Forests)

## 📊 Datasets Used
- S&P 500 (2012–2025) from Yahoo Finance
- Russell 3000 (2015–2025) from Alpha Vantage API (`TIME_SERIES_DAILY`)

## 📈 Key Findings
- PCA is highly effective for capturing linear structure, but autoencoders approach or exceed its performance on nonlinear patterns as model capacity increases.
- Autoencoder-based clustering reveals latent groupings (e.g., NFLX and TSLA) not found in PCA results.
- Anomaly detection is more robust when incorporating autoencoder reconstruction loss and multivariate Isolation Forests.

## 🔗 Report
The full project report is written in LaTeX and available in `report.pdf` or [`main.tex`](main.tex). It includes methodology, figures, and citations.

## 📎 Citation
If you found this useful, consider citing the project or referencing the GitHub repo directly.