# A Machine Learning Approach to Detect Early Signs of Startup Success
[Abhinav Nadh Thirupathi](http://www.linkedin.com/in/abhinavthirupathi)<sup>1</sup>,
[Tuka Alhanai](https://talhanai.xyz/)<sup>2</sup>,
[Mohammad M. Ghassemi](https://ghassemi.xyz/)<sup>1</sup><br>
<sup>1</sup> Michigan State University <sup>2</sup> New York University Abu Dhabi

Data and Code for "A Machine Learning Approach to Detect Early Signs of Startup Success", published in the 2nd ACM International Conference on AI in Finance (ICAIF 2021). 


## Abstract

In this study, we investigate a heterogeneous set of startup ven- tures (different ages, products, teams, levels of maturity, etc.) to identify the time-independent factors associated with their future success. More specifically, we investigated 3,160 unique companies, all of which were recipients of Small Business Innovation Research (SBIR) or Small Business Technology Transfer (STTR) awards. For each company, we collected any publicly available information: the SBIR/STTR award (amount, agency, principal investigator, etc.), and Crunchbase business profile. The collected data were used to train a XGBoost model that predicts whether a company had an initial public offering (IPO), and/or merged with, and/or was acquired by another entity (M&A). The performance of the model assessed using leave one-out-cross validation (LOOCV) was strong: 84% accuracy and 0.91 AUC. We found that employees with entrepreneurial expe- rience, arts, and/or STEM educational backgrounds, among other characteristics played a significant role in predicting the success of small businesses. Our results indicate that machine learning models may be used to assess the viability of small ventures.

## In this Repository

- `data`
  - `study` contains the company-level and people-level data utilized in the paper.
- `analysis.ipynb` is the Jupyter Notebook that contains the analyses presented in the paper.  
- `figures` contains the figures used in the paper
  - `data_preparation_pipeline.pdf` shows the five steps of the data preparation pipeline used in this paper
  - `reliability_diagram.pdf` shows the statistical calibration of the model developed in this paper
  - `SHAP_feature_importance.pdf` shows the top 10 features of the model based on the mean absolute SHAP values in this paper


## How to Cite
```
@inproceedings{thirupathi2021mlstartupsuccess,
      title={A Machine Learning Approach to Detect Early Signs of Startup Success}, 
      author={Abhinav Nadh Thirupathi and Tuka Alhanai and Mohammad M. Ghassemi},
      booktitle={2nd ACM International Conference on AI in Finance (ICAIF'21)},
      year={2021}
}
```
