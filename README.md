# Computational-Linguistics

# Motivation
The Voynich Manuscript provides an interesting opportunity to apply the techniques that we have learned in this class to a dataset that is not a confirmed language. In this paper, we will analyze the language in the Voynich manuscript using the following techniques: 

1. word length comparisons
2. hidden Markov models
3. arithmetic compression.

By comparing the above analyses run on the Voynich manuscript to known languages, we believe that there is some evidence that the Voynich manuscript really be a valid language. 

# Conclusion
When comparing Voynich to common languages at a static statistical level (e.g., looking at frequency of word length and other static statistics), it appears that there may be evidence that Voynich is not a true language. These statistics are measures for how similar Voynich is to the reference language, but they are not as good at identifying underlying hidden structure in an unknown language that may suggest that it comes from a coherent system that has different “statistics” to known languages. For this sort of analysis, we use the HMM model trained on Voynich and the arithmetic compression analysis. These analyses seem to indicate the Voynich has a strong coherent hidden structure, which while different from common European languages, is sufficient to suggest that it could be a real language. 