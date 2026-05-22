# Dataset

The pipeline trains and evaluates on the 20-newsgroups corpus, fetched lazily
by `sklearn.datasets.fetch_20newsgroups(subset='train')` /
`fetch_20newsgroups(subset='test')`.

- 20 categories.
- ~11,300 documents in train, ~7,500 in test.
- The download is cached under `~/scikit_learn_data/` by default.

The pipeline reports macro-averaged accuracy on the test split as its headline
metric.
