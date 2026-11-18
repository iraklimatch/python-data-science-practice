# Python & data science practice notebooks

Hands-on practice for a Python and data-science coding interview, built around energy and utility data: transformers, sensor readings, outages, grid load and smart meters. Each exercise has a short task, an empty cell for your code, an automatic **check** that tells you ✅ or ❌ (and why), a hint, and a hidden solution. Some exercises are “say it out loud” prompts with model answers.

Everything runs in Google Colab with no setup. The data is synthetic and is generated inside each notebook.

| Notebook | What it covers | Open |
|---|---|---|
| **00 · Foundations** | variables, types, strings, if/else, loops, lists, dicts, functions, errors, files, first steps in NumPy, pandas and ML (19 exercises) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iraklimatch/python-data-science-practice/blob/main/notebooks/00_foundations.ipynb) |
| **01 · Python interview basics** | mutable defaults, sets, Counter, generators, sliding windows, interval merging, decorators, comprehensions, classes, two-sum (17 exercises) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iraklimatch/python-data-science-practice/blob/main/notebooks/01_python_interview_basics.ipynb) |
| **02 · pandas** | selection, data quality, gap filling, groupby, resample, rolling z-scores, merge_asof labels, pivots, joins, SQL-style queries (12 exercises) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iraklimatch/python-data-science-practice/blob/main/notebooks/02_pandas.ipynb) |
| **03 · Machine learning** | pipelines, metrics for rare events, precision@k, permutation importance, time-series CV, forecasting, Isolation Forest, grid search, overfitting, from-scratch gradient descent, k-means, bootstrap (16 exercises) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iraklimatch/python-data-science-practice/blob/main/notebooks/03_machine_learning.ipynb) |
| **04 · Mock exam** | a timed 45-minute exercise on messy smart-meter data: cleaning, daily usage, suspicious meters, a risk model, and explaining results | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iraklimatch/python-data-science-practice/blob/main/notebooks/04_mock_exam.ipynb) |

## How to use

1. Click **Open in Colab**, then **File → Save a copy in Drive**. Without that copy, Colab won't keep your edits.
2. Run the first cell (**▶ Run me first**). It creates the practice data and the checker.
3. For each exercise: write your code, press **Shift + Enter**, then run the `check(...)` cell under it.
4. Stuck? Open **🔎 Hint**. Still stuck? Open **💡 Show a solution**, then close it and type the answer yourself.
5. Run `progress()` at the end to see which exercises you've passed.

All solutions are tested to pass with the library versions Colab ships (pandas 2.2, scikit-learn 1.6) and with newer ones.
