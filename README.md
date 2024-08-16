## Enhancing trauma triage in low-resource settings: a comparative study of machine learning models and the Kampala Trauma Score (KTS)

This repository contains the code, data, and analysis scripts used for the study on enhancing trauma triage in low-resource settings using machine learning models. The study evaluates the performance of several machine learning (ML) models, including Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machine, in predicting clinical outcomes for trauma patients. These models were benchmarked against the Kampala Trauma Score (KTS) to assess their effectiveness in a low-resource setting.

### Repository Contents

- **data.xlsx**: The dataset containing trauma registry information from Soroti Regional Referral Hospital in Uganda, which was used for model training and evaluation.
- **descriptive.Rmd**: An R Markdown file that includes descriptive statistical analysis of the trauma dataset, generating insights on patient demographics, injury characteristics, and clinical outcomes.
- **descriptive.html**: An HTML output of the descriptive analysis from the `descriptive.Rmd` file, providing an easy-to-view format of the statistical summaries and visualizations.
- **models.ipynb**: A Jupyter Notebook containing the Python code used to build, train, and evaluate the ML models. This notebook includes the preprocessing steps, model training, cross-validation, and performance metrics calculation.

### Usage

To use the code and data in this repository:
1. Clone the repository.
2. Ensure that you have the necessary R and Python environments set up to run the scripts and notebooks.
3. Run `descriptive.Rmd` for the descriptive statistical analysis and view the results in `descriptive.html`.
4. Use `models.ipynb` to train and evaluate the ML models.

### Citation

If you use this code, data, or the results from this study in your research, please cite our paper:

**TODO

## License

This repository is licensed under the MIT License. 
