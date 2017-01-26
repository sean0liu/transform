# Tensorflow Transform

TFTransform is a framework for transforming data with TensorFlow.
It allows users to combine transformations defined in terms of functions that
act on tensors, with full pass operations that analyze the entire dataset.
By doing so we allow users to construct complex transformations involving
vocabularies, normalization and bucketizing, while allow a user to easily
incorporate these transformations into the serving graph.