# OK GPT-2: write me a melancholic song: Conditional lyrics generation with fine-tuned GPT-2 and PPLM


This repository has been created to host the code and the dataset that have been used for the final project of the Natural Language Processing course held by prof. Fabio Tamburini at the University of Bologna. The repository includes a paper that explains in depth the whole projects.

Natural Language Generation (NLG) is a sub-field of Natural Language Processing (NLP)
in which the main task consists of generating samples of text from language models. Despite
major advances in the field of NLP, generating texts conditioned under a specific attribute is
still a rather complicated issue. The usual approach is limited to fine-tuning a pre-trained model
with a specific corpus in order to get an output shaped on the training dataset. Plug and Play
Language Model aims at stirring the generation of samples of text by using specific attributes,
without re-doing the training each time. This work explores the possibilities of generating
musical lyrics by fine-tuning a GPT-2 model and using PPLM to condition the generation of
text. The results are only partially satisfactory: fine-tuning GPT-2 to obtain samples of lyrics
proved to be an easy task, while using the trained model with PPLM shows some inconsistency
between the bag-of-words approach and the classifiers one
