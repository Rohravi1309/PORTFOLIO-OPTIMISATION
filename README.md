# Portfolio Optimization using Principal Component Analysis (PCA)

## Overview

This project demonstrates the application of Principal Component Analysis (PCA) for portfolio optimization. The goal is to transform original asset returns data into a lower-dimensional space defined by principal components, capturing essential patterns while reducing noise and redundancy. The optimized portfolios outperform standard benchmarks by maximizing returns and minimizing variance.

## Features

- **Principal Component Analysis (PCA)**: Reduces dimensionality of asset returns data, focusing on key components that drive portfolio performance.
- **Portfolio Construction**: Utilizes PCA-transformed data to build portfolios optimized for variance and returns.
- **Benchmark Comparison**: Compares the optimized portfolio's performance against benchmarks, such as an equally weighted portfolio.

## Libraries and Tools

- **Python**: The core programming language used.
- **Numpy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **yfinance**: For fetching historical financial data.

## Getting Started

### Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas matplotlib yfinance
