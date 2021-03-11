# sub_sentence_sentiment
Project to score phrases within sentences according to sentiment

## Code

The file *simple_inference_pipeline.ipynb* is a first attempt at creating a baseline for this project using only heuristics and existing (pre-trained) models.

It is a Jupyter notebook which allows you to input a multi-part sentence, and see that sentence with postive and negative sentiment phrases color coded green and red respectively. Sentences are broken into phrases on conjunctions (and, but, or, etc.).

## TODO:

- Improve exisitng pipeline using more heuristics to break sentences, besides conjunctions.
- Add training pipeline using data from Stanford NLP "Sentiment Treebank" dataset (with custom model).
- Compare new pipeline to baseline pipeline and iterate on datasets, features, and models.

## Inspiration

Use of conjunctions and other planned heuristics inspired by this paper:

https://www.researchgate.net/publication/314424838_Negation_Handling_in_Sentiment_Analysis_at_Sentence_Level

Dataset found at:

https://nlp.stanford.edu/sentiment/index.html

Future potential resource:

https://arxiv.org/pdf/1806.00807.pdf
