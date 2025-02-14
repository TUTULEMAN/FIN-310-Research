# **Portfolio Allocation and Risk Analysis Research**

## **Overview**
This repository contains the research paper, data analysis, and Monte Carlo simulations for optimizing portfolio allocation based on risk-adjusted returns.

## **Repository Structure**
- **`latexraw.tex`** – The LaTeX source file for the research paper, containing all findings, methodology, and results.
- **`JupterNotebokDisplay.ipynb`** – The Jupyter Notebook containing all data analysis, risk-return calculations, portfolio allocation, and Monte Carlo simulations.
- **`Research Paper.pdf`** – The "real sauce" that shows all of my findings in a research-paper-based presentation. **`latexraw.tex`** is what makes up this file.

## **How to Use**
1. **Research Paper (`latexraw.tex`)**  
   - Open this file in Overleaf or a LaTeX editor to compile the final report.
   - Ensure all figures and references are properly linked before compiling.

2. **Data Analysis (`JupterNotebokDisplay.ipynb`)**  
   - Open the Jupyter Notebook in **Jupyter Lab** or **Google Colab**.
   - Install necessary dependencies using:
     ```bash
     pip install yfinance numpy pandas matplotlib seaborn
     ```
   - Run each cell sequentially to reproduce data retrieval, portfolio allocation, and Monte Carlo simulations.

## **Results Summary**
- **Portfolio Performance:** Mean simulated portfolio value: **\$523,339.35**  
- **Risk Assessment:** Portfolio standard deviation: **\$20,498.36**  
- **Suggested Improvement:** Expand asset universe beyond 100 stocks/ETFs for better risk-adjusted returns.

## **Acknowledgments**
This research was conducted as part of **FIN 310 (46871), UIC Class '27, BS. Finance + Maths**, under the **"How The Market Works"** project for **Egemen Genc's** class.

