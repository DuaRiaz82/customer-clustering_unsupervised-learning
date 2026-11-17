# customer-clustering_unsupervised-learning
# Customer Segmentation with K-means

A small unsupervised-learning project that groups mall customers by annual income and spending score. It includes a Jupyter notebook documenting the analysis and a Streamlit app for exploring the five customer segments interactively.

## Project files

- `Lab 4 - Customer Segmentation (K-means).ipynb` — walkthrough of the data exploration, preprocessing, K-means clustering, and customer segments.
- `Mall_Customers.csv` — original customer dataset.
- `Mall_Customers_clean.csv` — cleaned customer data used by the app (`gender`, `age`, `income`, and `spending`).
- `segment_model.pkl` — saved clustering model, scaler, segment names, and marketing suggestions.
- `app.py` — Streamlit application.
- `requirements.txt` — Python package dependencies.

## Run the app

Use Python and install the listed dependencies in a virtual environment:

```bash
python -m venv .venv
```

Activate it, then install the packages:

```bash
# Windows PowerShell
.\.venv\Scripts\Activate.ps1

# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
```

Start the app from the project directory:

```bash
streamlit run app.py
```

The app lets you choose a customer's annual income (in thousands of dollars) and spending score. It predicts the segment, shows a marketing suggestion, and plots the customer alongside the dataset.

## Explore the notebook

To run the analysis notebook, install the dependencies above and launch Jupyter:
##LIVE LINK

http://localhost:8501/

```bash
jupyter notebook
```

Open `Lab 4 - Customer Segmentation (K-means).ipynb`. The notebook uses `Mall_Customers.csv` as its source data.
