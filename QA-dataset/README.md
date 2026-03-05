## Huggingface autotrain

1. *autotrain_data_fransen* folder contains files for fine-tuning BERT-architecture models for extractive-QA with autotrain on the dataset constructed from data extracted from the paper on biodegradability of polyesters [1]. Because of some features of the autotrain, impossible questions are removed from *validation.json*, but they are present in *train.json* and *test_with_impossible.json*
