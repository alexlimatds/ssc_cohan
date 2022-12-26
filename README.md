# ssc_cohan
Implementation of the Sequential Sentence Classification model proposed by Cohan et al (2019).

Cohan et al (2019) propose a strategy of how exploit BERT to deal with the Sequential Sentence Classification (SSC) task: we concatenate sentences by inserting a \[SEP\] token between two subsequent sentences; we feed BERT with the concatenation, or block of sentences, and we perform classification from the embeddings of \[SEP\] tokens.

This notebook replicates Cohan et al (2019) models. The dataset was also published by them in the same work and it's available at https://github.com/allenai/sequential_sentence_classification.

### References:
- Arman Cohan, Iz Beltagy, Daniel King, Bhavana Dalvi, Dan Weld. **Pretrained Language Models for Sequential Sentence Classification**. 2019. EMNLP.
