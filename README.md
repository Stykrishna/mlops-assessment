## AI/ML Assessment – MLOps Pipeline

### What was implemented
I created a simple ML pipeline using the Iris dataset. A baseline model (Logistic Regression) was trained first. Then an improved model (Random Forest) was trained and evaluated. A conditional logic step was added to compare both models and deploy the new model only if it performs equal or better than the baseline.

### How to run
1. Open the Jupyter notebook `mlops_assessment.ipynb`.
2. Run all cells from top to bottom.
3. The production model will be saved as `production_model.pkl`.

### Assumptions
- The Iris dataset is used as a sample real-world classification problem.
- Accuracy is used as the evaluation metric.
- No external model registry is used; comparison is done locally.

## Reflection on Coding Assistant

Using a coding assistant helped me complete the task faster, especially for structuring the ML pipeline and implementing the conditional deployment logic. It provided useful suggestions for model selection and evaluation. However, I still needed to review the code to ensure it matched the assessment requirements. The assistant was most helpful in generating boilerplate code and explaining MLOps concepts.
