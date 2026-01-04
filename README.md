# babyllm-tokenization


This repository contains a Colab notebook for studying different tokenization strategies (Character, Byte-Pair Encoding (BPE), and Byte-Level Transformer (BLT)) in the context of a simplified Transformer language model. The goal is to compare their performance, particularly on linguistic generalization tasks using the BLIMP dataset.

## Project Overview

This project implements and compares three different tokenization methods: 

1.  **Character-level Tokenization (Char)**: Each character is treated as a token.
2.  **Byte-Pair Encoding (BPE)**: A subword tokenization algorithm trained on the dataset.
3.  **Byte-Level Transformer (BLT)**: A custom model that processes raw bytes directly, incorporating pooling layers.

The models are trained on a subset of the WikiText-2 dataset and then evaluated on the BLIMP dataset, which is designed to test specific linguistic phenomena.
