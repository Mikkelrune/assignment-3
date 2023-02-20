# assignment-3
Assignment for BDS


# The assignment is builed on data from reddit. In the notebook you will find 3 different approaches on how to use the data. 

# 1. Language translation. This is done by using an encoder-decoder architecture which is prebuilt in the pretrained model from huggingface. The encoder takes the input sentence and converts it into a fixed-length vector representation, which is then fed into the decoder. The decoder generates the output sentence one word at a time, using the encoded input and the previously generated words as context. In our case with the data is translate from english to french as you can see in the code. 

# 2. Zero Shot Classification.  The method here is the model classifies the data into different labels. The term "zero-shot" refers to the fact that the model can classify instances into classes it has never seen before, without being trained on any examples of those classes. Reminder (to increase the accuracy find better dataset) pretty bad accuracy in the current ZSC

# 3. The last approach is built in question answering model. A Question Answering (QA) model is a type of machine learning model that is designed to automatically answer questions posed in natural language. In our case we get pretty bad resultats because of the data we are using.
