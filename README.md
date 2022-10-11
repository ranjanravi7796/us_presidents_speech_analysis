# us_presidents_speech_analysis
Text analysis on Inaugural speeches of all USA presidents

In this project, I collected the Inaugural speeches of all USA presidents starting from the 1st USA president Washington (1789) to the 46th USA president Joe Biden. After that, I have performed preprocessing such as removing the stopwords and punctuations, and then performed lemmatization. 
My analysis includes below:

1. Which president has the most vocabulary as evident from their inaugural speeches, and which president has the least vocabulary? On average, do Democratic, Republican, or Other presidents have higher vocabulary?

2. Create a barplot of presidential vocabulary from the earliest president (Washington) to the latest (Biden) in chronological order. Color code this barplot as blue for Democrat, red for Republican, and gray for Others.

3. What are the five most frequently used words (exclusive of stop words) used by each president? What are the five most frequently words used collectively by all Democratic presidents versus Republican presidents?

4. What are the key themes (e.g., freedom, liberty, country, etc.) used by each president in their inaugural speech?

5. Compute a sentiment (positive/negative) for each presidential speech, and draw a barplot of the sentiment of all presidential speeches in chronological order. Again, color code the speeches as blue for Democrat, red for Republican, and gray for Other. Which of these groups have higher mean sentiment score? Who are the top three presidents with the highest positive sentiment in each group?

For the above analysis, I have used NLTK library for capturing the sentiment and the vocabularies of the speech. Later on, for finding the key theme (topic) of the speech, I performed a topic modelling technique called Latent Dirichlet Allocation (LDA). Based on this technique, I assigned each speech to a topic which contains a list of words.

As I started learning the concepts of Natural Language Processing (NLP), I wanted to work with some interesting text data. Therefore, I felt why not take a real world text data (USA presidents speeches) in this case and try out what I have learnt.
