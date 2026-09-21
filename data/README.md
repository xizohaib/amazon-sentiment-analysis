# Dataset

The Amazon Fine Food Reviews dataset used in this project was obtained from Kaggle.

The original dataset contains approximately 568,454 Amazon food product reviews.

The dataset is not included in this repository because of its large size.

## Dataset Columns

The original dataset contains the following columns:

- Id
- ProductId
- UserId
- ProfileName
- HelpfulnessNumerator
- HelpfulnessDenominator
- Score
- Time
- Summary
- Text

For sentiment analysis, the main columns used were:

- `Text` - Customer review text
- `Score` - Product rating

## Sentiment Labels

Reviews were converted into binary sentiment classes:

- Scores 1–2 → Negative
- Scores 4–5 → Positive
- Score 3 → Removed as neutral

Download the dataset from Kaggle and place the CSV file in the `data/` directory before running the notebook.
