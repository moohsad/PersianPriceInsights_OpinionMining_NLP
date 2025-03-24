# PersianPriceInsights: Advanced Opinion Mining on DigiKala Comments

**PersianPriceInsights** is a cutting-edge project in Natural Language Processing (NLP) designed to extract actionable insights from Persian user comments on DigiKala, Iran's leading e-commerce platform. By leveraging state-of-the-art machine learning techniques, this repository analyzes a massive dataset of customer feedback to detect mentions of product pricing—an essential aspect of understanding consumer behavior and market dynamics. This project showcases two robust implementations, each tailored to deliver high accuracy and scalability, making it a valuable resource for researchers, data scientists, and businesses aiming to harness the power of Persian text data.

## Project Significance
DigiKala, as the largest online retailer in the Middle East, generates an immense volume of user-generated content daily. With over 40,000 labeled comments in the training set alone, this dataset represents a goldmine for opinion mining and sentiment analysis. Detecting price-related feedback is not just a technical challenge—it’s a strategic tool for e-commerce platforms to refine pricing strategies, enhance customer satisfaction, and stay competitive in a dynamic market. This project stands out by tackling Persian NLP, an underrepresented area in global research, and delivering production-ready solutions with real-world impact.

## Dataset
- **Source**: Comments from DigiKala, provided in `train.csv` (40,000 labeled samples) and `test.csv` (8,000 unlabeled samples).
- **Features**: 
  - `comment`: Raw Persian text of user reviews.
  - `price_value`: Binary target (0: no price mention, 1: price mentioned).
- **Scale**: With 48,000 total samples, this dataset offers a substantial benchmark for Persian NLP tasks.

## Requirements
- **Python**: 3.10 or higher
- **Dependencies**: 
  ```bash
  pip install -r requirements.txt
