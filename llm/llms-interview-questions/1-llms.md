# LLMs

source: [Amazon](https://aws.amazon.com/what-is/large-language-model/), [wiki](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture)), [IBM](https://www.ibm.com/think/topics/encoder-decoder-model)

## What are Large Language Models?

Large language models, also known as LLMs, are very large deep learning models that are pre-trained on vast amounts of data. The underlying transformer is a set of neural networks that consist of an encoder and a decoder with self-attention capabilities. The encoder and decoder extract meanings from a sequence of text and understand the relationships between words and phrases in it.

Transformer LLMs are capable of **unsupervised training**, although a more precise explanation is that transformers perform **self-learning**. It is through this process that transformers learn to understand basic grammar, languages, and knowledge.

Unlike earlier recurrent **neural networks (RNN) that sequentially** process inputs, **transformers process entire sequences in parallel**. This allows the data scientists to use GPUs for training transformer-based LLMs, significantly reducing the training time.

Transformer neural network architecture allows the use of very large models, often with hundreds of billions of parameters. Such large-scale models can ingest massive amounts of data, often from the internet, but also from sources such as the Common Crawl, which comprises more than 50 billion web pages, and Wikipedia, which has approximately 57 million pages.

## Transformer (deep learning architecture)
The transformer is a **deep learning architecture** that was developed by researchers at Google and is based on the **multi-head attention mechanism**, which was proposed in the 2017 paper "Attention Is All You Need". **Text is converted to numerical representations called tokens, and each token is converted into a vector** via lookup from a word embedding table. At each layer, each token is then contextualized within the scope of the context window with other (unmasked) tokens via a **parallel multi-head attention mechanism**, allowing the signal for key tokens to be amplified and less important tokens to be diminished.

Transformers have the advantage of having **no recurrent units, therefore requiring less training time** than earlier recurrent neural architectures (RNNs) such as long short-term memory (LSTM)


## Encoder& Decoder

In deep learning, the encoder-decoder architecture is a type of neural network most widely associated with the transformer architecture and used in **sequence-to-sequence** learning. Literature thus refers to encoder-decoders at times as a form of sequence-to-sequence model (seq2seq model).

Encoder-decoder models are used to handle sequential data, specifically mapping input sequences to output sequences of different lengths, such as neural machine translation, text summarization, image captioning and speech recognition. 

**Encoder encodes a given input into a vector representation**, and the **decoder decodes this vector into the same data type as the original input dataset**.

Both the encoder and decoder are separate, fully connected neural networks. They may be recurrent neural networks (RNNs)—plus its variants long-short term memory (LSTM), gated recurrent units (GRUs)—and convolutional neural networks (CNNs), as well as transformer models. An encoder-decoder model typically contains several encoders and several decoders.

Each encoder consists of two layers: the self-attention layer (or self-attention mechanism) and the feed-forward neural network. The first layer guides the encoder in surveying and focusing on other related words in a given input as it encodes one specific word therein. The feed-forward neural network further processes encodings so they are acceptable for subsequent encoder or decoder layers.

The decoder part also consists of a self-attention layer and feed-forward neural network, as well as an additional third layer: the encoder-decoder attention layer. This layer focuses network attention on specific parts of the output of the encoder. The multi-head attention layer thereby maps tokens from two different sequences.2

### How encoder-decoder models work
Literature widely presents encoder-decoder models as consisting of three components: the encoder, the context vector, and the decoder.

#### Encoder

The principal component of the encoder is the self-attention mechanism. The self-attention mechanism determines token weights in a text input to reflect inter-token relationships. In contrast to a traditional word embedding that ignores word order, self-attention processes the whole input text sequence to compute each token’s weighted average embedding that takes into account that token’s distance from all of the other tokens in the text sequence. It computes this average embedding as a linear combination of all embeddings for the input sequence.

## What is sentiment analysis?
Sentiment analysis, or opinion mining, is the process of analyzing large volumes of text to determine whether it expresses a positive sentiment, a negative sentiment or a neutral sentiment.