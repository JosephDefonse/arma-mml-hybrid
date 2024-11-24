<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">MML in Hybrid ARMA-LSTM Model Forecasting</h1>
  <p align="center">
    A hybrid model combining ARMA and LSTM for improved time series forecasting, leveraging Minimum Message Length (MML) for model selection.
    <br />
    <a href="https://www.mdpi.com/1099-4300/23/12/1601">View Paper</a>
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
        <li><a href="#technologies">Technologies, Mathematics & Proofs</a></li>
      </ul>
    </li>
    <li>
      <a href="#repository-contents">Repository Contents</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#dataset">Dataset</a></li>
      </ul>
    </li>
    <li>
      <a href="#results">Results</a>
    </li>
    <li>
      <a href="#roadmap">Roadmap</a>
    </li>
    <li>
      <a href="#contact">Contact</a>
    </li>
    <li>
      <a href="#references">References</a>
    </li>
  </ol>
</details>

---

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> About The Project </h2>

Forecasting in time series is a complex task, often hindered by trends, seasonal components, and non-stationarity. This project explores the integration of two methodologies—traditional statistical models like ARMA and deep learning architectures like LSTM—to improve forecasting accuracy.

Using the Minimum Message Length (MML) criterion for model selection, this project compares MML’s performance against other commonly used criteria such as AIC, BIC, and HQ. The hybrid ARMA-LSTM model leverages the strengths of ARMA for linear components and LSTM for capturing complex nonlinear residual patterns.

### Key Features:
- **Hybrid Modeling**: Combines ARMA for linear dependencies and LSTM for nonlinear patterns.
- **MML-Based Model Selection**: Implements MML to optimize ARMA model selection, outperforming AIC, BIC, and HQ.
- **Extensive Mathematical Framework**: Includes detailed mathematical proofs for ARIMA, SARIMA, AIC, BIC, and MML, along with forward and backward propagation in LSTM.
- **Comparative Analysis**: Evaluates ARIMA and ARIMA-LSTM models across various forecasting horizons (T).

<p align="right">(<a href="#top">back to top</a>)</p>

---

<h2 id="technologies"> Technologies, Mathematics & Proofs </h2>

This project integrates cutting-edge tools with rigorous mathematical derivations:
- **Technologies**:
  - Python
  - Statsmodels (for ARMA modeling)
  - TensorFlow/Keras (for LSTM modeling)
  - PyTorch (alternative LSTM implementation)
  - Pandas and NumPy (data manipulation and analysis)
  - Matplotlib (visualization)

- **Mathematics**:
  - Detailed derivations of ARIMA, SARIMA, AIC, BIC, and MML.
  - Proofs of compact forms of ARMA and SARIMA equations.
  - Comprehensive understanding of RNNs and LSTMs, including backpropagation with mathematical derivations.

For a complete understanding, refer to the report: **"Mathematical Proofs and Concepts in Time Series Analysis for Stock Predictions Using ARIMA-LSTM Hybrid Model.pdf"**.

<p align="right">(<a href="#top">back to top</a>)</p>

---

<h2 id="repository-contents"> Repository Contents </h2>

- **`arma.ipynb`**: Jupyter Notebook implementing ARMA model forecasting and predictions on stock data.
- **`lstm.ipynb`**: Jupyter Notebook implementing ARIMA-LSTM hybrid model forecasting and predictions on the same dataset.
- **`MMM_full.csv`**: The dataset containing stock data used for modeling and prediction.
- **`Mathematical Proofs and Concepts in Time Series Analysis for Stock Predictions Using ARIMA-LSTM Hybrid Model.pdf`**: A comprehensive report detailing the theoretical and mathematical foundations, implementation, and results.

<p align="right">(<a href="#top">back to top</a>)</p>

---

<!-- GETTING STARTED -->
<h2 id="getting-started"> Getting Started </h2>

To replicate or extend this project locally, follow these steps:

<h3 id="installation"> Installation </h3>

1. Clone the repository:
```sh
git clone https://github.com/your-repo/MML_ARMA_LSTM.git