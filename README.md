# 🍺 Beer Datasets

This repository contains individual, ready-to-use datasets in **CSV format**, compressed using `.gz`, and extracted from the public BeerAdvocate archive. Each dataset is available as a separate `.csv.gz` file for modular use in data pipeline testing, CDC simulations, and batch processing experiments.

---

## 📦 Available Datasets

| File             | Description                                     | Rows (approx)  |
|------------------|-------------------------------------------------|----------------|
| `brewery.csv.gz` | Brewery ID and name                             | 5,800+         |
| `beer.csv.gz`    | Beers with style, ABV, and brewery reference    | 66,000+        |
| `profile.csv.gz` | Simulated user profiles based on profile names  | 33,000+        |
| `review.csv.gz`  | Full reviews with scores and tasting notes      | 1.5M+          |

> 🔹 **All files are in CSV format and compressed with Gzip (`.gz`).**

> ⚠️ **Note:** The data in `profile.csv.gz` is fully synthetic. It was generated using Faker and is intended **exclusively for testing purposes**.

---

## 🚀 Using with Data Master CLI

```bash
# Download and extract a specific dataset
datamaster seed --dataset beer
