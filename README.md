# PP4 supervised learning

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP4-supervised-learning/blob/master/PP4_supervised_learning.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/PP4-supervised-learning/blob/master/LICENSE)

Practical Project 4 (PP4) for Artificial Intelligence studies to solidify **supervised learning** basics by practicing.

## Usage

### Automatic launch

For Windows installation just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/PP4-supervised-learning/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/PP4-supervised-learning.git
```

2. Navigate into project:

```bash
cd PP4-supervised-learning/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook PP4_supervised_learning.ipynb
```

## Requirements

- [X] Choose any dataset (can be found in kaggle, scikit inbuilt datasets, or find them anywhere on the internet, or even use generated - any source is acceptable. The only requirement for the generated datasets is that they must have noise >=0.3 in them)
- [X] Choose a problem you want to solve. The problem must be a supervised learning problem - regression or classification.
- [X] Using k-fold cross validation (CV) and/or GridSearch/RandomizedSearch tune a model/ensemble until you get best possible result.
- [X] Include proof of the process of tuning (for example two cells where you tried some model parameters and another cell where you tried others).
- [ ] Visualize results - please be sure to visualize the final predictions: decision boundary (classification) or the regression line (regression) need to be added.
- [ ] Provide a scoring metric - choose as appropriate (r2_score, f1 score, auROC and so on).
- [ ] Provide a short paragraph (3-10 sentences) on why do you think the parameters you found were the best? Was it related to data distribution, shape, clear decision boundary, dimensionality, etc.?
- [X] Provide Google Colab link (or GitHub link with .ipynb file).

Extra bonus: tune the model with and without PCA - answer the question: was PCA useful for your specific situation to achieve higher accuracy. Include proof of the process of tuning (for example two cells where you tried some model parameters and another cell where you tried others).
