# Transliteration
## Hindi-to-English-Transliteration-using-Seq2Seq-encoding

## We will transliterate English text into Hindi using Sequence to Sequence model.

I used seq2seq model to implement encoder-decoder, you can refer to this keras official documentation :
https://keras.io/examples/nlp/lstm_seq2seq/

## Summary of the algorithm

RNNs are also capable of doing natural language translation, machine translation and  transliteration. It involves two RNNs, one for the source language and one for the target language. One of them is called an encoder, and the other one decoder. The reason is that, the first one encodes the sentence into a vector and the second one converts the encoded vector into a sentence in target language.

# Performance
BLEU (BiLingual Evaluation Understudy) is a metric for automatically evaluating machine-translated text. The BLEU score is a number between zero and one that measures the similarity of the machine-translated text to a set of high quality reference translations. A value of 0 means that the machine-translated output has no overlap with the reference translation (low quality) while a value of 1 means there is perfect overlap with the reference translations (high quality).
It has been shown that BLEU scores correlate well with human judgment of translation quality. Note that even human translators do not achieve a perfect score of 1.0.

# dataset

[Download the Dataset](http://workshop.colips.org/news2018/dataset.html)
1. Under the “NEWS2018 DATASET_04” section, you will find Hindi mentioned.
2. Press the “request data” link to register &amp; get the download link.
3. After downloading the dataset, have a look at the Hindi training set and validation set XML files.