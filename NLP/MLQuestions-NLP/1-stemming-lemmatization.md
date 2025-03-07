# Stemming & Lemmatization

source: [IBM](https://www.ibm.com/think/topics/stemming-lemmatization): 

- Stemming: The stemmer then removes any found suffix character strings from the word, should the latter not defy any rules or conditions attached to that suffix. Some stemmers (for example, Lovins stemmer) run the resulting stemmed bits through an additional set of rules to correct for malformed roots. The most widely used algorithm is the Porter stemming algorithm, and its updated version the Snowball stemmer. 
    - example: caring --> car

- Lemmatization: as the larger enterprise of reducing morphological variants to one dictionary base form. 
    - caring --> care

- main difference: The practical distinction is that, where stemming merely removes common suffixes from the end of word tokens, lemmatization ensures the output word is an existing normalized form of the word (for example, lemma) that can be found in the dictionary.

- limitations: 
    - Development of stemming and lemmatization algorithms for other languages, notably Arabic. Arabic is particularly challenging due to its agglutinative morphology, orthographic variations, and lexical ambiguity, among other features. In all, such elements problematize a systematic method for identifying base word forms among morphological variants, at least when compared to English words.
    - over-stemming: when two semantically distinct words are reduced to the same root (for example, news to new).
    - under-stemming: when two words semantically related are not reduced to the same root (for example, knavish and knave to knavish and knave respectively)