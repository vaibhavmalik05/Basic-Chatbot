# Basic Chatbot
 In this repo we have build a chatbot which give answers based on the corpus that we have selected. We can also select the large corpus, But for this example we have selected only Data Science wikipedia page text. So our answer will be based on that only.

## Preprocessing steps taken:

1. Tokenization
2. Stop words removal
3. Punctuations Removal (Applied filter on what punctuation we want to keep)
4. Lowering of text.
5. Lemmatization.

## Model

Here we have used TFIDF (with user defined tokenizer function as a hyperparameter for word tokenizing) and fit-transform on setence tokenizer.

word and sentence tokens are updated based on user input text.
