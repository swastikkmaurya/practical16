# practical16

Aim: To implement core Natural Language Processing (NLP) preprocessing steps using the NLTK library, including Tokenization, Stemming, Lemmatization, and POS Tagging.

Theory:

Natural Language Processing (NLP) is a branch of Artificial Intelligence and computational linguistics that enables computers to understand, interpret, and generate human language. Text data — found in emails, social media posts, customer reviews, news articles, medical records, and legal documents — is one of the most abundant forms of unstructured data available today. Unlike structured tabular data, raw text cannot be used directly in mathematical models and must first be processed into a structured numerical form.

pd.merge(df1, df2, on='Key'): Combines two DataFrames into one by matching rows based on a specific common column.

how='inner': A parameter in the merge function that keeps only the rows where the joining key exists in both DataFrames.

how='outer': A parameter that retains all rows from both DataFrames, filling in missing values with NaN where no match is found.

how='left': A parameter that keeps all rows from the first (left) DataFrame and only the matching rows from the second (right) DataFrame.

how='right': A parameter that keeps all rows from the second (right) DataFrame and only the matching rows from the first (left) DataFrame.

df.columns: Accesses and lists the names of all columns present in a DataFrame.

df.shape: Returns the dimensions of the DataFrame, showing the total number of rows and columns.

df.info(): Provides a concise summary of the DataFrame, including data types, non-null counts, and memory usage.

df.describe(): Generates basic descriptive statistics (like mean, count, and standard deviation) for the numerical columns in the dataset.

print(df): Outputs the contents of the DataFrame to the console for inspection.

Environment Setup: Download necessary NLTK datasets (punkt, stopwords, wordnet, averaged_perceptron_tagger).

Tokenization:

1.Split the string into a list of words using word_tokenize.

2.Split the paragraph into individual sentences using sent_tokenize.

3.Cleaning: Filter out tokens that exist in the NLTK English stopword list to reduce noise.

4.Morphological Reduction:

5.Apply the Porter Stemmer to reduce words to their stems.

Apply the WordNet Lemmatizer to find accurate dictionary roots.

Syntactic Analysis: Use pos_tag to label each word with its Part-of-Speech tag (e.g., NNP for Proper Noun, VBZ for Verb).

6.Frequency Analysis: Utilize FreqDist to calculate and display the occurrences of each word to identify the most dominant terms in the text.

Conclusion:

NLP Techniques on Text Data using Python and the NLTK library were successfully studied and implemented
