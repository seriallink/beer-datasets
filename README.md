# 🍺 Beer Datasets

This repository contains individual, ready-to-use datasets in **CSV format**, extracted and enriched from the public BeerAdvocate archive. Each dataset is packaged as a separate `.zip` file for modular use in data pipeline testing, CDC simulations, and batch processing experiments.

---

## 📦 Available Datasets

| File          | Description                                    | Rows (approx)  |
|---------------|------------------------------------------------|----------------|
| `brewery.zip` | Brewery ID and name                            | 5,800+         |
| `beer.zip`    | Beers with style, ABV, and brewery reference   | 66,000+        |
| `profile.zip` | Simulated users profile based on profile names | 33,000+        |
| `review.zip`  | Full reviews with scores and tasting notes     | 1.5M+          |

> 🔹 **All files are in CSV format.**

> ⚠️ **Note:** The data in `profile.zip` is fully synthetic. It was generated using Faker and is intended **exclusively for testing purposes**.

---

## 🚀 Using with Data Master CLI

```bash
# Download and extract a specific dataset
datamaster seed --dataset beer
