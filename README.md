

# Sentiment Analysis of Prince Lyrics

This project performs sentiment analysis on the lyrics of Prince's songs using text mining techniques. The analysis includes preprocessing the text, performing sentiment analysis using various lexicons, and visualizing the results.

## Project Structure

- **Load Libraries**: Install and load required packages.
- **Read Data**: Load the dataset `prince_text.csv`.
- **Modify Data**: Preprocess and modify the dataset for analysis.
- **Tokenize and Preprocess Text**: Tokenize the text and clean it by removing unwanted words.
- **Match Ratio Calculation**: Calculate the match ratio between the tidy text data frame and three lexicons (bing, NRC, Afinn).
- **Sentiment Analysis**: Perform sentiment analysis using the "nrc" lexicon.
- **Contributing Words**: Identify words contributing to sentiment scores.
- **Positive Words by Song**: Determine which songs use the most positive words.
- **Mood Analysis**: Analyze the mood of specific songs.
- **Polarity by Chart Level**: Analyze polarity by chart level using the Bing lexicon.
- **Polarity by Decades**: Analyze polarity by decades using the Bing lexicon.

## Installation

To replicate this analysis, you need to have R installed on your machine. Install the required packages using the following commands:

```r
install.packages('tidyverse')
install.packages('tidytext')
install.packages('sotu')
install.packages('dplyr')
```

## Usage

1. **Load and Preprocess Data**:
   - Load the Prince lyrics data from `prince_text.csv`.
   - Preprocess the text by fixing contractions and tokenizing the text.

2. **Text Cleaning and Tokenization**:
   - Clean the text by fixing contractions.
   - Tokenize the text into individual words.
   - Remove stop words and undesirable words.

3. **Sentiment Analysis**:
   - Calculate the match ratio between the text and three sentiment lexicons (bing, NRC, Afinn).
   - Perform sentiment analysis using the NRC lexicon.
   - Identify the words contributing most to sentiment scores.
   - Determine which songs use the most positive words.
   - Analyze the mood of specific songs like "Sign O’ the Times" and "So Blue".

4. **Visualization**:
   - Visualize the sentiment scores using bar plots.
   - Plot the sentiment scores over time to observe trends.
   - Visualize the polarity by chart level and decades using the Bing lexicon.



## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

