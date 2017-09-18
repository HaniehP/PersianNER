# PersianNER
Named-Entity Recognition in Persian Language

## ArmanPersoNERCorpus 
This is the first manually-annotated Persian Named-Entity (NE) dataset with ISLRN 399-379-640-828-6. We are releasing it only for academic research use.
The dataset includes 250,015 tokens and 7,682 Persian sentences in totall. It is avaiable in 3 folds of training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. Each sentence is separated with a new line.
NERtags are in IOB format. According to the instructions provided to the annotators, NEs are categorized into six classes person, organization (such as banks, ministries, embassies, teams, nationalities, networks and publishers), location (such as cities, villages,rivers, seas, golfs, deserts and mountains), facility (such as schools, universities, research centers, airports, railways, bridges, roads, harbors, stations, hospitals, parks, zoos and cinemas), product (such as books, newspapers, TV shows, movies, airplanes, ships, cars, theories, laws, agreements and religion), and event (such as wars, earthquakes, national holidays, festivals and conferences); other are the remaining tokens. 

Please cite [1,2] if you use this dataset.

## Persian Word Embeddings

GloVe300d, word2vec_cbow300d, word2vec_skipgram300d, and hpca300d are four different word embeddings trained on a sizable collation of Persian text. Please cite [1] if you use any of these word embeddings.

### Citations

1. Hanieh Poostchi, Ehsan Zare Borzeshi, Mohammad Abdous, and Massimo Piccardi, "PersoNER: Persian Named-Entity Recognition," In the 26th International Conference on Computational Linguistics (COLING 2016), pages 3381–3389, Osaka, Japan, 2016.

2. "BiLSTM-CRF for Persian Named-Entity Recognition; ArmanPersoNERCorpus: the First Entity-Annotated Persian Dataset," In the 11th edition of the Language Resources and Evaluation Conference (LREC), Miyazaki, Japan, 7-12 May 2018 (Under review).
