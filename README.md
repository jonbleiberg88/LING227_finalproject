# LING227_finalproject
Jonathan Bleiberg - December 2018

## Dependencies:

    Python 3, keras, sci-kit learn, numpy, scipy, gensim, string, pyenchant, Pyphen, matplotlib, nltk, random
    
## Brief File Descriptions:

**hard_coded_embeddings.ipynb**:  Implementation of hardcoded stylistic embeddings on the Gutenberg and Brown corpora; helper functions to facilitate embedding construction; 2D TSNE and PCA visualizations

**doc2vec.ipynb**:  Implementation of Doc2Vec embeddings on the Gutenberg and Brown corpora; 2D TSNE and PCA visualizations

**synonym_pertubation.ipynb**: First implementation of synonym perturbation embeddings on first 5000 words of Gutenberg and Brown corpora; helper functions to extract synonyms via cosine similarity; 2D TSNE and PCA visualizations

**synonym_pertubation2.ipynb**: Second implementation of synonym perturbation embeddings on first 5000 words of Brown corpus with wordnet and cosine similarity synonym generation method; helper functions to extract synonyms via combined cosine similarity and wordnet approach; 2D TSNE and PCA visualizations

**synonym_pertubation3.ipynb**: Third implementation of synonym perturbation embeddings on first 10000 words of Gutenberg and Brown corpora with tweaked hyperparameters, experiments with hidden layer size, regularization, BatchNorm, and Dropout; helper functions to extract synonyms via combined cosine similarity and wordnet approach; 2D TSNE and PCA visualizations


## Data/Models:

**10000_words_data_compressed.npz** - Compressed version of the dataset from synonym_pertubation3.ipynb compiled from first 10000 words of Gutenberg and Brown corpora, combined wordnet and cosine similarity synonym approach

**brown_first_5000.h5**:  Saved version of first model trained on first 5000 words of Brown corpus

**gutenberg_first_5000.h5**: Saved version of first model trained on first 5000 words of Gutenberg corpus

**brown_first_5000_v2.h5**: Saved version of second model trained on first 5000 words of Brown corpus

**combined_first_10000_v2.h5**: Saved version of model trained on first 10000 words of Combined Brown/Gutenberg Corpus
