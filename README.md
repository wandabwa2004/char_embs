# Comprendes

(Comprend~o/es/e/emos/an) #wedntreadwords

Decoupling and recombining syntactic (character-level) and semantic (contextual) similarity in distributed string embeddings.

The idea is to:

	* capture the signal for syntactic similarity on the character level.

	* capture the signal for semantic (contextual) similarity, e.g. via word-embeddings, to gain access to the semantic space structure beyond syntactic similarity.

	* decypher (model) the meaning for (embed) OOV strings


## Motivation/Applications

* Social media (misspellings)

* Identifiers e.g. column headers in tables or databases, Twitter handles, etc.

* Multilingual data (linguistic similarities across languages e.g. italian/spanish)


## Requirements

The model has to tolerate the following corruptions in textual data by indicating syntactic similarity 

* upper/lower casing
* spacing (presence or absence as well as the variety of the word-level delimiters)
* omition/inflaction of substrings
* reordering of substrings


## Related Work

### Text Similarity

* CHARAGRAM: Embedding Words and Sentences via Character n-grams ACL 2016 (PDF)[https://aclweb.org/anthology/D16-1157]

### Language Modeling
* Character-Aware Neural Language Models (AAAI 2016) (Code)[https://github.com/yoonkim/lstm-char-cnn]

### Text Classification

* Character-level Convolutional Networks for Text Classification	nips		2015
(PDF)[https://papers.nips.cc/paper/5782-character-level-convolutional-networks-for-text-classification.pdf]

### Text Clustering

* Semi-supervised Clustering for Short Text via Deep Representation Learning

* Self-Taught Convolutional Neural Networks for Short Text Clustering

* Short Text Clustering via Convolutional Neural Networks