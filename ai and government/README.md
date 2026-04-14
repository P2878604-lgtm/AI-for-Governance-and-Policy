# COMPAS Recidivism Algorithm Replication

Replication of ProPublica's 2016 "Machine Bias" analysis examining racial bias in the COMPAS recidivism prediction algorithm.

## Original Study
- ProPublica (2016). "Machine Bias". Available at: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
- Original code: https://github.com/propublica/compas-analysis

## Quick Start
pip install -r requirements.txt
jupyter notebook replication.ipynb
# Then: Kernel → Restart & Run All

## Data Source
Data from ProPublica's COMPAS analysis repository:
https://github.com/propublica/compas-analysis

The dataset contains records of ~10,000 criminal defendants from Broward County, Florida.

## Repository Structure
- replication.ipynb - Main replication notebook
- data/compas-scores-two-years.csv - COMPAS dataset
- requirements.txt - Python dependencies
- README.md - This file
