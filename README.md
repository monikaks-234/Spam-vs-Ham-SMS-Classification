# Spam vs Ham SMS Classification

## Project Overview

This project analyzes SMS text messages and classifies them as **Spam** or **Ham** (not spam).
It is implemented in a Jupyter Notebook (`Spam_Ham_Analysis.ipynb`) using Python, and includes:

* Exploratory Data Analysis (EDA)
* Text Preprocessing
* Feature Engineering (TF-IDF Vectorization)
* Model Building (Naive Bayes, Logistic Regression, etc.)
* Model Evaluation
* Visualization of results

## Dataset

The project uses the **SMS Spam Collection Dataset**, a well-known dataset of labeled SMS messages.

* Columns:

  * `label`: Spam or Ham
  * `message`: The actual SMS text

## Requirements

* Python 3.x
* Jupyter Notebook / Jupyter Lab
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* nltk

## How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/spam-ham-classification.git
   cd spam-ham-classification
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Spam_Ham_Analysis.ipynb
   ```

4. Run the notebook cells step-by-step to reproduce the analysis and model results.

## Results

* The best performing model is Naive Bayes with accuracy of **xx%** (fill in your model performance here).
* Visual insights are provided through EDA and word clouds.

## Project Structure

```
├── Spam_Ham_Analysis.ipynb
├── README.md
├── requirements.txt
└── data/
    └── spam.csv  # or your dataset filename
```

## Future Work

* Hyperparameter tuning
* Use of advanced models (e.g., deep learning)
* Deployment as a simple web app

## License

This project is licensed under the MIT License.
