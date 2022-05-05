In this repository, NLP summarization algorithms were tested. 

With the help of WordCloud, it is possible to do a simple exploratory data analysis through a visual representation of words. The top 100 popular words and phrases based on frequency and relevance are visualized. 
After preprocessing has been held. Preprocessing is always a crucial part when it comes to building NLP models. In the notebook preprocessing is in pipeline for building algorithms. Next steps of preprocessing used:
- Lowercasing the text
- Removing the punctuation
- Removing the stopwords
- Tokenizing the text
- Stemming and Lemmatization of the text

For my task I used 2 main text summarization methods:
- Extractive summarization.
- Abstractive summarization

Extractive Summarization 

The main idea of Extractive Summarization is to evaluate phrases or sentences from the text and extract only the most important sentences, which will build the summary.

Abstractive Summarization

Abstractive Summarization aims to generate a new summary text by rephrasing sentences The encoder outputs masked tokens while the decoder generates Gap sentences. Models that I will use for this task are Bert and XLNet(both from Google).
