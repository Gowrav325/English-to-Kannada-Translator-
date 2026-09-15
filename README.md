# English to Kannada Neural Machine Translation

An English-to-Kannada Neural Machine Translation (NMT) system built with PyTorch

Overview

This project implements an LSTM-based Sequence-to-Sequence (Seq2Seq) model with an attention mechanism to translate English sentences into Kannada, addressing syntactic differences and vocabulary sparsity between the two languages.

Key Highlights

    Seq2Seq Architecture: Built an LSTM encoder-decoder model augmented with an attention mechanism to capture cross-lingual token alignments during translation.

    Pretrained Embeddings: Leveraged pretrained GloVe embeddings for English source sentences and Indic-BERT representations for target Kannada vocabulary.

    Optimization & Training: Trained using the Adam optimizer with scheduled teacher forcing to enhance autoregressive decoding and gradient clipping to stabilize training.

    Evaluation: Evaluated translation fluency across multi-gram BLEU scores (BLEU-1 through BLEU-4).

Repository Contents

    english-to-kannada-translation.ipynb — End-to-end notebook covering data preprocessing, embedding loading, model architecture, training loop, and evaluation.

    README.md — Project summary and setup.
