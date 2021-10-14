"A Machine Learning Approach to Detect Early Signs of Startup Success" has been accepted to be published in the 2nd ACM International Conference on AI in Finance (ICAIF 2021). 

## Abstract

In this study, we investigate a heterogeneous set of startup ven- tures (different ages, products, teams, levels of maturity, etc.) to identify the time-independent factors associated with their future success. More specifically, we investigated 3,160 unique companies, all of which were recipients of Small Business Innovation Research (SBIR) or Small Business Technology Transfer (STTR) awards. For each company, we collected any publicly available information: the SBIR/STTR award (amount, agency, principal investigator, etc.), and Crunchbase business profile. The collected data were used to train a XGBoost model that predicts whether a company had an initial public offering (IPO), and/or merged with, and/or was acquired by another entity (M&A). The performance of the model assessed using leave one-out-cross validation (LOOCV) was strong: 84% accuracy and 0.91 AUC. We found that employees with entrepreneurial expe- rience, arts, and/or STEM educational backgrounds, among other characteristics played a significant role in predicting the success of small businesses. Our results indicate that machine learning models may be used to assess the viability of small ventures.

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

## In this Repository

To train the model(s) in the paper, run this command:
- `study_data.csv` contains the company-level and people-level data utilized in the paper.
- `analysis.ipynb` is the Jupyter Notebook that contains the analyses presented in the paper.  
- `supplementary-materials.pdf` contains the detailed information not included in the paper.

## How to Cite
```
@inproceedings{thirupathi2021startupsuccess,
      title={A Machine Learning Approach to Detect Early Signs of Startup Success}, 
      author={Abhinav Nadh Thirupathi and Tuka Alhanai and Mohammad M. Ghassemi},
      booktitle={ICAIF 2021: Proceedings of the Second ACM International Conference on AI in Finance},
      year={2021}
}
```
