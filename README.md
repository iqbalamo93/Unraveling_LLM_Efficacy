# Effective Rank Metrics for Evaluating Large Language Models (LLMs)

![Build Status](https://img.shields.io/badge/Build-Passing-green) ![Version 1.0](https://img.shields.io/badge/Version-1.0-blue) ![MIT License](https://img.shields.io/badge/License-MIT-orange)

## Overview

This repository provides a comprehensive framework for evaluating Large Language Models (LLMs) using new metrics, including Effective Rank. It serves as an extension to Mahoney's foundational work, offering a multi-faceted approach that blends theoretical mathematics and practical AI research. Through correlation, regression, and pairwise analyses, this repository aims to be a resource for both academic and real-world applications.

## Features

- **Effective Rank Metrics**: Introducing new metrics to evaluate LLMs
- **Correlation Analysis**: Deep dive into correlating parameters and performance
- **Regression Analysis**: Predictive modeling based on eigenvalue distributions
- **Pairwise Analysis**: Comparative study among various LLMs
- **Helper Utilities**: Tools for downloading LLMs' weight matrices
- **Ethically Inclusive**: Designed with ethical considerations and sustainability in mind

## File Structure

\```bash
.
├── 01_LLM_Analysis
│   └── (Correlation analysis files)
├── 02_LLM_Analysis
│   └── (Regression analysis files)
├── 03_Pair_diff
│   └── (Pairwise analysis files)
├── 99_LLM_Comparisions
│   └── (Helper files)
├── 99_LLM_Profiler_14_34
│   └── (Helper files for LLMs 14-34)
├── 99_LLM_Profiler_35_41
│   └── (Helper files for LLMs 35-41)
└── README.md
\```

## Usage

1. **01_LLM_Analysis**: This folder contains the correlation analysis between different parameters and LLM performance.
  
2. **02_LLM_Analysis**: This folder hosts files related to the regression analysis.

3. **03_Pair_diff**: Inside you'll find the pairwise comparative analysis of various LLMs.

4. **99_LLM_Comparisons**, **99_LLM_Profiler_14_34**, **99_LLM_Profiler_35_41**: These are helper folders that contain utilities for downloading weight matrices. The last numbers signify the model numbers.

5. **99_LLM_Profiler_35_41**: This folder consolidates all the above-mentioned helper files.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License. See the `LICENSE.md` file for details.
