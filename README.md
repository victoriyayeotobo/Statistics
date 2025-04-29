# Predicting Brain Responses with Nonlinear Regression and Bayesian Inference

This project explores predicting brain response signals (MEG) based on auditory stimuli using nonlinear polynomial regression techniques.  
It combines classic regression modeling with Bayesian methods to not only fit the data but also quantify uncertainty in key model parameters.

---

## Objective

To model the relationship between auditory stimuli features and brain response signals using advanced regression techniques, select the most parsimonious model, and use Bayesian inference (Approximate Bayesian Computation) to understand uncertainty in parameter estimates.

---

## My Learning Focus

- **Data Exploration**:  
  Visualized distributions, time series patterns, and detected nonlinearity in brain response signals.
  
- **Model Building and Selection**:  
  Developed five polynomial regression models with increasing complexity and selected the best one based on RSS, Log-Likelihood, AIC, and BIC.

- **Residual Diagnostics**:  
  Conducted Q-Q plots and residual histograms to verify Gaussian assumptions required for model validity.

- **Applying Approximate Bayesian Computation (ABC)**:  
  Estimated the posterior distributions of the two most influential parameters to assess confidence in model predictions.

- **Real-World Thinking**:  
  Learned that good modeling isn’t just about fitting data — it's about balancing model complexity, validating assumptions, and understanding parameter uncertainty for better decision-making.

---

## Tools and Libraries

- Python  
- NumPy, pandas  
- matplotlib, seaborn  
- scikit-learn  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/victoriyayeotobo/Statistics.git
   cd Statistics
2. Install the required libraries:
   pip install -r requirements.txt

3. Run the notebook:
   Open Statistics_correct.ipynb in Jupyter Notebook or Google Colab.
   
Note: This project helped me appreciate the full modeling pipeline — from exploring real-world data to building models, validating assumptions, and using Bayesian techniques to understand deeper insights beyond point estimates.
