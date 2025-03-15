# Assignment-AE-3-
Application Exercise (AE#3): Data Analysis and Visualization
Reflection
1. Explain the type of data you used and the activities you completed.
For this assignment, we used the Nobel Prize Winners dataset, which contains information about Nobel laureates from 1901 to 2017. The dataset includes details such as the winner’s name, birth and death locations, prize category, year awarded, and a "motivation" column that describes why they received the award.

Our primary focus was on the motivation text, as it provided valuable insights into the reasoning behind each prize. To analyze this data, we:

Cleaned the text by removing missing values, converting it to lowercase, and removing duplicates.
Performed sentiment analysis using the Bing Lexicon, categorizing motivations as positive, neutral, or negative based on sentiment scores.
Visualized the results using histograms and bar charts to understand sentiment distribution across different Nobel Prize categories.
This approach helped us explore how different fields, such as Peace and Literature, might have more positive sentiment, while scientific fields like Medicine or Physics might contain more neutral or technical language.

2. Describe your experience using R and any issues you encountered.
Using R for this assignment was an insightful experience, but we encountered several challenges along the way.

Package Installation Issues: We initially had trouble installing required libraries (tidytext, textdata) in Posit Cloud, as some required additional dependencies.
Tokenization Problems: When breaking the "motivation" column into individual words using unnest_tokens(), the column disappeared, causing errors.
Fixing Missing Context: To resolve this, we ensured that motivation text remained linked to the winner’s name and removed stop words to improve sentiment accuracy.
Despite these challenges, R proved to be a powerful tool for text analysis. We learned valuable skills in data cleaning, text processing, and visualization, which will be beneficial for future projects.

3. Do you think you will use this software and process again in the future?
Yes, I believe R and sentiment analysis will be useful in future projects, especially in areas involving text mining, opinion analysis, and content evaluation.

Potential applications include:

Analyzing customer reviews to understand brand perception.
Tracking public opinion in news articles and political speeches.
Studying academic research trends by analyzing abstracts and keywords over time.
Additionally, this process could be beneficial for analyzing book reviews, movie scripts, or song lyrics to detect emotional themes. Now that we understand how to clean and process text data, we can apply these techniques to real-world problems across multiple industries.

4. Which data analysis technique did you choose and why?
We chose sentiment analysis because it allowed us to quantify the tone of Nobel Prize motivations and determine whether they conveyed positive, neutral, or negative sentiment.

Unlike other techniques like topic modeling or clustering, which group words based on similarity, sentiment analysis directly measures emotional tone and provides a clear interpretation of the data.

This was particularly relevant for our dataset because Nobel Prize motivations describe groundbreaking discoveries, humanitarian contributions, or historical events—many of which evoke strong positive or serious tones. By visualizing sentiment distribution, we gained insights into how different Nobel Prize categories tend to be perceived emotionally.

For example:

Peace and Literature prizes often have more positive sentiment due to their humanitarian nature.
Science-related prizes (Physics, Chemistry, Medicine) may contain neutral or technical language without strong sentiment.
By using sentiment analysis, we could detect patterns and trends in Nobel Prize motivations, providing an interesting perspective on how different fields are acknowledged and appreciated over time.
