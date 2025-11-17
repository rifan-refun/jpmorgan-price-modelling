# **JP Morgan Job Simulation** 
## Natural Gas Forecasting and Pricing Modelling Prototype

This repository contains a structured exploration of financial price modelling as part of a technical assessment / job simulation. The project focuses on building a price modelling workflow using Python, financial datasets, and structured engineering practices.

## Project Overview

The objective of this project is to implement a simplified price modelling framework. This includes:

- Working with structured time-series financial data  
- Performing exploratory data analysis (EDA)  
- Building a modelling pipeline for predicting price movement  
- Implementing clean, modular Python code  
- Presenting a transparent reasoning process behind the modelling decisions  

This project demonstrates a mix of **applied machine learning and statistics**, **data engineering workflow**, **practical reasoning in finance-oriented modelling** and **clean programming paradigm**.

## Key Features

- 📊 **Financial Dataset Exploration**  
  Statistical summaries, visualization, acf and pacf plot.

- 📈 **Machine Learning Pipeline (Baseline)**  
  - Interpolation and extrapolation
  - Modelling
  - Evaluate and validation
  - Inferencing result
  - Prototype modelling

## How to Run This Project

This project can be executed either in **Google Colab** or **Jupyter Notebook** on your local machine.  
Follow the instructions below.

# Option 1 — Run on Google Colab (Recommended)

### **1. Open a new Colab notebook**
Go to: https://colab.research.google.com

### **2. Clone this GitHub repository**
Run this in a Colab cell:

```bash
!git clone https://github.com/rifan-refun/jpmorgan-price-modelling.git
```

```bash 
%cd jpmorgan-price-modelling
```

```bash 
notebooks/price_modelling.ipynb
```

# **Option 2 - Run on local jupyter notebook**

### **1. Clone this GitHub repository**
```bash
git clone https://github.com/rifan-refun/jpmorgan-price-modelling.git
cd jpmorgan-price-modelling
```
### **2. Install requirements**
```bash
pip install -r requirements.txt
```
### **3. Launch Jupyter Notebook**
```bash
jupyter notebook
```

### **4. Run jupyter notebook**
```bash 
notebooks/price_modelling.ipynb
```

