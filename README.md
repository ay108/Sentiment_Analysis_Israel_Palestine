# Sentiment_Analysis_Israel_Palestine
## **Introduction:**

In this notebook, I aim to compare and contrast sentiment found in reddit commens related to the Israel-Palestine Genocide from earlier (~2023) and now (After Trump has been in office, starting January 2025).

There is already prior analysis done, where sentiment analysis and geopolitical stance classification was done. I aim to add to the conversation by analyzing how Trump's presence has or has not affected the composition of people who support Palestine or Israel.

This analysis is divided into 6 sections:

1. **Data Exploration and Cleaning:**
   - We start by loading Reddit comments from a CSV file and employ rigorous data cleaning methods. This includes removing URLs, HTML tags, special characters, and employing lemmatization for text normalization.


2. **Sentiment Analysis:**
   - Utilizing the VADER sentiment analysis tool, we assess the emotional tone of each comment. Four key sentiment metrics—Compound, Positive, Negative, and Neutral—are computed, offering a nuanced understanding of user sentiments.


3. **Exploratory Data Analysis:**
   - Through visualization techniques like density plots and word clouds, we visually represent sentiment distributions. This helps us identify prevailing positive, negative, and neutral sentiments within the dataset.


4. **Topic Modeling:**
   - Employing Latent Dirichlet Allocation (LDA), a popular topic modeling technique, we uncover latent topics within the comments. This step aids in comprehending the underlying themes that dominate the discussions.


5. **Geopolitical Stance Classification:**
   - By combining sentiment scores and dominant topics, we classify comments into distinct geopolitical stances. Users are categorized based on their sentiments—support for Israel, support for Palestine, opposition to Israel/Palestine, or a neutral stance where the user's position remains ambiguous.


6. **Insights and Conclusions:**
   - Through this in-depth analysis, we gain valuable insights into the sentiments and geopolitical inclinations prevalent in Reddit discussions on the Israel-Palestine conflict. This exploration sheds light on the diverse opinions within the online community, providing a comprehensive overview of public sentiment.
