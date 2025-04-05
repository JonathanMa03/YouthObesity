# Obesity of the Youth: Health Disparity and Income Inequality

![NSCH](https://img.shields.io/badge/Data-NSCH%202019%20%26%202023-blue)
![License](https://img.shields.io/badge/License-Academic-lightgrey)
![Status](https://img.shields.io/badge/Project-Active-green)

## Overview

This project investigates the structural and behavioral determinants of adolescent obesity in the United States, with a focus on **income inequality**, **healthcare access**, and **racial/ethnic disparities**. Using nationally representative data from the **National Survey of Children’s Health (NSCH)** for 2019 and 2023, we estimate logistic models and compute inequality indices to explore how social determinants shape health outcomes in youth.

---

## Objectives

- Analyze the impact of **socioeconomic, racial, and healthcare factors** on adolescent obesity.
- Compare **pre- and post-COVID** trends in obesity using year-fixed effects.
- Apply the **PRECEDE-PROCEED** public health framework to interpret results.
- Quantify inequality using the **Concentration Index** and **Kakwani Index** by subgroup.

---

## Methodology

- **Data Source**: National Survey of Children’s Health (NSCH) 2019 & 2023
- **Model**: Pooled logistic regression with marginal effects
- **Inequality Metrics**: Concentration Index (CI), Kakwani Index
- **Framework**: PRECEDE-PROCEED model used for behavioral context

---

## Repository Structure

```bash
├── data/                  # Raw, Cleaned, and Transformed NSCH data
├── code/                  # R files for data preparation, model, and concentration index
│   ├── Obesity.Rmd        
│   ├── LogitModel.Rmd
│   └── ConcIndex.Rmd
├── output/                # Figures, tables, and regression output
├── presentation/          # Written output
│   ├── Abstract        
│   ├── Poster
|   ├── Presentation
└── README.md              # Project overview and instructions
