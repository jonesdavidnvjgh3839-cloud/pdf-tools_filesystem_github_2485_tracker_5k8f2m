# Provenance Registry

Catalog ID: ghfht9135k3m9p7

This registry tracks the lineage of Northwind Labs internal analytics datasets. Each derived dataset lists its upstream source dataset(s) using internal short codes.

| Dataset ID | Type | Upstream Sources |
|------------|------|------------------|
| SRC-SST2 | source | — |
| SRC-IMDB | source | — |
| SRC-TWEET | source | — |
| DRV-SENTIMENT | derived | SRC-SST2 |
| DRV-REVIEWS | derived | SRC-IMDB |
| DRV-SOCIAL | derived | SRC-TWEET |
| DRV-FULL | derived | [stanfordnlp/sst2](https://huggingface.co/datasets/stanfordnlp/sst2), [cardiffnlp/tweet_eval](https://huggingface.co/datasets/cardiffnlp/tweet_eval) |
