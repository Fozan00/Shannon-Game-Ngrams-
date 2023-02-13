# Shannon-Game-Ngrams

Built the bigram and the trigram language models.

Took a corpus realdonaldtrump.csv. Removed any links

Splitted data into 80% training and 20% test sets.

Removed punctuation marks. But as the full stop is the sentence marker, kept it in the text in case in need to tokenize sentences.

Removed the newline characters.

Removed stopwords.

Used the n-grams module from nltk.util package to build bigrams and trigrams.

Find the frequencies of bigrams and trigrams in the corpus. Tabulate them and show the histogram.

Did Add-1 smoothing (Laplace)

Built a dictionary showing bigram and trigram probabilities against each sorted in increasing order.

Retabulated the reconstituted counts for the bigrams and the trigrams.

Again plotted histograms

Took a four-word string as the test sample and find both its unigram, bigram, and trigram perplexities.

Natural Langauge Generation Task: Based on step 7, build CDF (Cumulative Distribution Function). Generate a random number and compared it with the CDF. Picked the word whose CDF value is closest to it and return it as the generated text.

Built the Shannon game. Predict the last word (hide it during prediction time) of the tweets in the test set based on one word before (Bigram modeling). Evaluated the results using accuracy.
