# Text Summarization

source: [IBM](https://www.ibm.com/think/topics/text-summarization),

Text summarization condenses one or more texts into shorter summaries for enhanced information extraction. Automatic text summarization (or document summarization) is a natural language processing (NLP) method that condenses information from one or more input text documents into an original output text. How much of the input text appears in the output is debated—some definitions state only 10%, others 50%.

## Extractive summarization 
extracts unmodified sentences from the original text documents. A key difference between extractive algorithms is how they score sentence importance while reducing topical redundancy. Differences in sentence scoring determines which sentences to extract and which to retain.

## Abstractive summarization 
generates original summaries using sentences not found in the original text documents. Such generation requires neural networks and large language models (LLMs) to produce semantically meaningful text sequences.


As one may guess, abstractive text summarization is more computationally expensive then extractive, requiring a more specialized understanding of artificial intelligence and generative systems. Of course, extractive text summarization may also utilize neural networks transformers—such as GPT, BERT, and BART—to create summaries. Nevertheless, extractive approaches do not require neural networks.

## Extractive vs abstractive summarization
 For instance, while some research suggests that abstractive summarization is more prone to hallucinations—that is, misleading or factually false information.3 Additional research, however, suggests that abstractive hallucinations actually align with world knowledge, being derived from the summarization source material itself. Other comparisons of extractive and abstractive techniques show that each have their comparative benefits. While human users view abstractive summaries as more coherent, they also consider extractive summaries more informative and relevant. Research also suggests that the controversiality of text subject matter affects how users view respective summary types.