# Customer Review Sentiment Analysis for Online Women's Clothing Shop

This project focuses on analyzing customer reviews for an online women's clothing shop. Using Python and the Natural Language Toolkit (NLTK), the goal is to evaluate customer sentiment across different clothing categories. By determining the overall satisfaction for each category (Tops, Bottoms, Jackets, Dresses, and Intimates), the shop can identify which products are most liked and which may need improvement based on customer feedback.

## Project Objective

The primary objective of this project is to perform sentiment analysis on customer reviews to understand customer satisfaction levels across different product categories. By analyzing the sentiment of the reviews, the shop can gain insights into customer preferences and improve product offerings and customer service.

## Approach

1. **Data Loading and Preprocessing:**
   - Load the customer reviews dataset.
   - Clean the text data by removing special characters, converting to lowercase, and handling missing values.

2. **Text Preprocessing:**
   - Tokenize the reviews to break them down into individual words.
   - Remove stopwords (common words like 'the', 'is', 'in') that do not contribute to sentiment.

3. **Feature Extraction:**
   - Extract adjectives from the reviews, as they are key indicators of sentiment (e.g., "good", "bad", "comfortable").
   - Explore the tokens and their frequencies to understand common words associated with each product category.

4. **Sentiment Analysis:**
   - Perform sentiment analysis using NLTK's sentiment analyzer to classify each review as positive, negative, or neutral.
   - Calculate the overall sentiment score for each product category to identify which category has the highest customer satisfaction.

5. **Visualization and Insights:**
   - Visualize the distribution of sentiment across categories using bar plots and word clouds.
   - Provide insights into customer feedback for each category and suggest potential improvements.

## Dataset Description

The dataset consists of customer reviews and related information, including:

- **Review Text:** The text of the customer review.
- **Clothing Category:** The product category (e.g., Tops, Bottoms, Jackets, Dresses, Intimates).
- **Review Rating:** The numeric rating given by the customer (optional).
- **Other Attributes:** Additional attributes like customer age, size, and fit (optional).

## Key Steps in the Project

1. **Loading the Dataset:**
   - Import the dataset using Pandas and inspect its structure.

2. **Text Cleaning and Preprocessing:**
   - Remove unwanted characters, convert text to lowercase, and handle missing values.
   - Tokenize the reviews and remove stopwords to focus on meaningful words.

3. **Exploratory Data Analysis (EDA):**
   - Explore the distribution of reviews across categories.
   - Visualize common words and phrases using word clouds and bar charts.

4. **Adjective Extraction:**
   - Extract adjectives from the reviews to understand customer sentiment better.

5. **Sentiment Analysis:**
   - Use NLTK's `VADER` sentiment analysis tool to classify each review as positive, negative, or neutral.
   - Calculate the overall sentiment score for each category.

6. **Results and Visualization:**
   - Visualize the sentiment distribution for each clothing category.
   - Identify which category has the highest and lowest customer satisfaction.

## Technologies Used

- **Python** for data analysis and sentiment analysis.
- **Pandas** for data manipulation and analysis.
- **NLTK** (Natural Language Toolkit) for text preprocessing and sentiment analysis.
- **Matplotlib** and **Seaborn** for data visualization.
- **WordCloud** for visual representation of common words in the reviews.

## Conclusion

This project successfully demonstrates the application of sentiment analysis to understand customer feedback in an online clothing shop. By analyzing customer reviews, we can identify which product categories have the highest and lowest satisfaction, providing actionable insights to improve product offerings and customer experience.

## Future Work

- **Advanced Sentiment Analysis:** Implement more advanced NLP techniques like BERT or TextBlob for improved sentiment analysis accuracy.
- **Topic Modeling:** Use topic modeling techniques to identify common themes in customer feedback.
- **Dashboard Creation:** Develop an interactive dashboard for real-time sentiment analysis and review monitoring.

## How to Run the Project

1. Clone the repository to your local machine.
2. Install the required Python libraries: `pandas`, `nltk`, `matplotlib`, `seaborn`, `wordcloud`.
3. Run the Jupyter Notebook or Python script to load and preprocess the dataset, and perform sentiment analysis.
4. Visualize the results using the provided visualization code snippets.
