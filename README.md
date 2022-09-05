# IdentifyME



Developed and trained a Caption Generator for images that brings
Xception Model which has been trained on imagenet dataset that had 1000 different classes to classify.

Performed data cleaning using Pandas and utilized the tokenizer function from the Keras Library to create tokens of the vocabulary.

Applied the Keras Model from Functional API which consists of Feature Extractor to reduce the dimension of the images to 256 nodes. A Sequence Processor where an embedding layer handles the textual input, followed by the LSTM layer. Finally, the decoder where we merge the output from the
above two layers, and process by the dense layer to make the final prediction.
