### Understand Text Summarization and create your own summarizer in python

Summarization can be defined as a task of producing a concise and fluent summary while preserving key information and overall meaning.

Impact
Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting. In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.

There are mainly two types of text summarization, i.e. Abstractive Summarization and Extractive Summarization
1. Abstractive Summarization: select words based on semantic understanding, even those words did not appear in the source documents. It can be correlated to the way human reads a text article or blog post and then summarizes in their own word.

Input document → understand context → semantics → create own summary.

2. Extractive Summarization: Extractive methods attempt to summarize articles by selecting a subset of words that retain the most important points.This approach weights the important part of sentences and uses the same to form the summary. 

Input document → sentences similarity → weight sentences → select sentences with higher rank.

Complete article with code and results can be found on [Medium](https://towardsdatascience.com/understand-text-summarization-and-create-your-own-summarizer-in-python-b26a9f09fc70)
