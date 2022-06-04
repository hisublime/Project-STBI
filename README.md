# Analysis Comparison of BM11 with BM25
We conduct experiments over two publicly available datasets:
- Song Lyrics is a public dataset by Deep Shah and consist of song lyrics of various artists. Specifically, the dataset that’s going to be used for this research is Taylor Swift lyrics.
- Friends Dialog is a dataset in .csv format that contains text files of all scenarios as well as dialogue for each episode on FRIENDS TV Show.

We compared BM11 with BM25 using two datasets namely: Song Lyrics and Friends datasets. In conducting the experiment, preprocessing is carried out on the dataset that will be used. The preprocessing consists of:
- Removing nul data
- Removing number and whitespace
- Tokenization
- Stopwords removal
- Punctuation.

Based on the experiments from our research, the comparison between BM11 and BM25 shows that BM25 is not always superior to BM11. This is based on our experimental results which show that the BM11 score is higher than the BM25 score. This score indicates the relevance between the query and the document in the experiment. This also refers to the literature review that we have done. Where it is stated that the BM25 score is weak for the occurrence of query terms in very long documents, and thus those very long documents can be overly penalized. Incidentally, the experiment we did was using long documents. Thus, BM25 is not really effective on long documents.
