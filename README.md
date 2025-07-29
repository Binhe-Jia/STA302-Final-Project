#  STA302 Final Project: Predicting Housing Sale Prices in Ames, Iowa

This project investigates which characteristics of a house most significantly influence its sale price, using a dataset of real estate transactions from Ames, Iowa. The analysis was conducted as the final group project for **STA302: Methods of Data Analysis** at the University of Toronto.

##  Research Question

> *What is the most significant characteristic of a house that impacts its sale price?*

We use multiple linear regression and various model diagnostics to determine how different house attributes, such as size, age, condition, and neighborhood, affect the final sale price.

##  Dataset

- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)
- **Description**: Contains 80 variables describing nearly every aspect of residential homes in Ames, Iowa, sold between 2006–2010.

##  Methods

- Data cleaning and variable selection based on missingness and relevance
- Multiple linear regression (MLR)
- Model selection via hypothesis tests, ANOVA, and Stepwise AIC
- Model diagnostics: residual analysis, VIF for multicollinearity, QQ plots
- Transformations for heteroskedasticity using Box-Cox and log transforms

##  Key Findings

- The most significant predictor of sale price is **above-ground living area** (`GrLivArea`), followed by **basement quality** and **garage size**.
- Some categorical variables (e.g., `Functional`, `BldgType`, and `Neighborhood`) showed significant effects on pricing, particularly in the presence of major defects or high crime rates.
- The final model achieved an **adjusted R² of 0.8561**, indicating strong explanatory power.

## ⚠ Limitations

- Dataset limited to a single city (Ames, Iowa); generalization is constrained.
- Some multicollinearity observed (VIF ~5), though considered manageable.
- Influential points were retained due to their contextual importance despite minor influence.

## 👥 Contributors

- **Binhe Jia** – Data analysis, modeling, and report writing  
- **William Kwan**  
- **Xiaoxu (Rita) Liu**

## 📚 References

- Kaggle Dataset: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Multiple academic sources and economic reports cited in the final report PDF.

---

