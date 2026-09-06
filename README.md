# House Rent Data Analysis

An Exploratory Data Analysis (EDA) on the **House Rent Prediction Dataset** (4,746 records) evaluating how property scale, furnishing status, and metropolitan tiers influence monthly rental valuations in major Indian cities.

---

## Central Analytical Question
> *"How do property dimensions (square footage), structural configuration (BHK), and furnishing status interact to drive monthly rent valuation across major metropolitan tiers, and how does spatial segmentation drive outlier premiums?"*

---

## Key Highlights & Operations

* **Pandas Exploration:** Data cleaning, type classification, missing/duplicate checks, and category profiling.
* **NumPy Implementation:** Array operations (`zeros`, `ones`, `arange`, `linspace`), slicing up to 3D, reshaping, transposition, and memory models (`flatten` copy vs. `ravel` view).
* **Vectorization & Broadcasting:** Sub-second vectorized computations, logarithmic transformations, and broadcasting adjustments.
* **Aggregations & Filtering:** Row-wise and column-wise axis operations, Boolean indexing, fancy indexing, and seeded reproducible sampling (`seed=42`).

---

## Core Findings

* **Location Drives Rent:** Metropolitan tiering dictates baseline price-per-square-foot elasticity more than physical area alone.
* **Furnishing Premium:** Furnished units command a clear upward price shift across identical floor plans.
* **Skewed Distribution:** Extreme luxury outliers pull the arithmetic mean upward; the median provides the accurate measure of central tendency.
* **Correlation vs. Cause:** Higher rents for furnished units reflect location-based confounding factors (prime zones) rather than furniture additions alone.
