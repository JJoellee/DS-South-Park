# DS-South-Park

This project aims to analyze the dialogue in South Park episodes to gain insights into the show's content and language use. The analysis will focus on the frequency of swear words and the overall sentiment of the dialogue in each episode. To accomplish this, the project uses a combination of data manipulation, text preprocessing, and sentiment analysis techniques.

The data for this project consists of South Park lines (sp_lines) and episode ratings (sp_ratings). The lines are tokenized into individual words and cleaned by removing stop words. Next, the project incorporates external resources such as a list of swear words and the AFINN lexicon to enrich the analysis. By cross-referencing the swear words list and applying stemming, the project identifies swear words in the dialogue. Additionally, using the AFINN lexicon, the sentiment score for each word is calculated.

The final output of this project is a data frame (sp_words) that contains information about each word's sentiment score, whether it's a swear word, and the episode it belongs to. This data can be further analyzed to study trends and patterns in the language and content of South Park episodes, such as the prevalence of swear words or the relationship between sentiment scores and episode ratings
