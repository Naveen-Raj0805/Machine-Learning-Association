# Market Basket Analysis using Association Rule Mining

## Project Overview
This repository contains a **Market Basket Analysis (MBA)** project designed to uncover hidden relationships between products purchased together by customers. By analyzing transaction history, this project uses data-mining techniques to discover strong association patterns, which help businesses optimize **product placement, marketing promotions, inventory management, and bundling strategies**.

## Core Concepts & Metrics
The model utilizes the **Apriori Algorithm** to extract frequent itemsets and generate Association Rules based on three key metrics:
* **Support**: Measures how frequently an item or itemset appears in the dataset.
* **Confidence**: Measures how often the rule is found to be true (conditional probability).
* **Lift**: Measures the strength of a rule over random chance. A lift value > 1 indicates that items are highly likely to be bought together.

## Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Mining/ML:** MLxtend (Apriori & Association Rules)
* **Visualization:** Matplotlib, Seaborn, NetworkX (for rule networks)
