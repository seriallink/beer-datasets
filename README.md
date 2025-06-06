# 🍺 Beer Datasets

This repository contains a curated and enriched dataset extracted from [BeerAdvocate](https://www.beeradvocate.com/), designed for testing data pipelines, CDC ingestion, analytical workloads, and sentiment analysis experiments.

## 📊 Dataset Overview

| Dataset  | Description                       | Format   | Approx. Rows |
|----------|-----------------------------------|----------|--------------|
| `brewery.csv` | Unique breweries with IDs and names     | CSV      | 5,800+       |
| `beer.csv`    | Beers with style, ABV, and brewery ID  | CSV      | 66,000+      |
| `user.csv`    | Simulated users (based on profile names, enriched with Faker) | CSV | 33,000+ |
| `review.csv`  | Reviews with scores and detailed text  | CSV      | 1.5M+        |

## 🛠️ Use Cases

- Test CDC pipelines (e.g., Aurora → DMS → Kinesis)
- Simulate streaming of users
- Run batch ingestion of review data
- Perform sentiment analysis with AWS Comprehend
- Explore Medallion architecture (bronze → silver → gold)
