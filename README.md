In this repository NLP summarization algorithm were tested. 

With the help of WordCloud it is possible to do the simple explaratory data analysis though a visual representation of words. Top 100 popular words and phrases based on frequency and relevance are visualised. 
After preprocessing has held. Preprocessing is always a crucial part when it comes to building a nlp models. In notebook preprocessing is in pipeline for building algorythms. Next steps of preprocessing used:
- Lowercasing the text
- Removing the punctuation
- Removing the stopwords
- Tokenizing the text
- Stemming and Lemmatization of the text

For my task I used 2 main text summarisation methods:
- Extractive summarization.
- Abstracttive summarization

Extractive Summarization 

The main idea of Extractive Summarization is too evaluate phrases or sentences from the text and extract only tthe most important sentences, which will build the summary.

Abstractive Summarization

Abstractive Summarization aim to generate a new summary text by rephrasing sentences The encoder outputs masked tokens while the decoder generates Gap sentences.Models that I will use for this task is Bert and XLNet(both from Google).
