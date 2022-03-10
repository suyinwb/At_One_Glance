# At One Glance
A repository of information & knowledge

We use statistical hypothesis testing to determine which of our hypotheses are most likely to be true. There are two types of statistical hypothesis:
* The null hypothesis is also known as H0 and is generally the hypothesis that can be explained by random chance.
* The alternate hypothesis is also known as Ha and is generally the hypothesis that is influenced by non-random events.


Hypothesis Testing in Five Steps
Regardless of the complexity of the dataset or the proposed question, hypothesis testing uses the same five steps:

Generate a null hypothesis, its corresponding alternate hypothesis, and the significance level.
Identify a statistical analysis to assess the truth of the null hypothesis.
Compute the p-value using statistical analysis.
Compare p-value to the significance level.
Reject (or fail to reject) the null hypothesis and generate the conclusion.

There are two main forms of the t-test that we use: the one-sample t-test and the two-sample t-test. The one-sample t-test is used to determine whether there is a statistical difference between the means of a sample dataset and a hypothesized, potential population dataset. In other words, a one-sample t-test is used to test the following hypotheses:

H0 : There is no statistical difference between the observed sample mean and its presumed population mean.
Ha : There is a statistical difference between the observed sample mean and its presumed population mean.

Before we can apply any statistical test to our data, we must check if there are any assumptions regarding our input dataset. When it comes to our one-sample t-test there are five assumptions about our input data:

The input data is numerical and continuous. This is because we are testing the distribution of two datasets.
The sample data was selected randomly from its population data.
The input data is considered to be normally distributed.
The sample size is reasonably large. Generally speaking, this means that the sample data distribution should be similar to its population data distribution.
The variance of the input data should be very similar.


## Natural Language Processing Core Concepts

1. Tokenization: splitting a document or sentence into small subsets of data that can be analyzed
Original sentence: I am enjoying learning about NLP.
Tokenized by word: ['I', 'am', 'enjoying', 'learning', 'about', 'NLP', '.']

Original sentence: There is a concept in NLP called tokenization. There are two types of tokenization: word and sentence.
Tokenized by sentence: ['There is a concept in NLP called tokenization.', 'There are two types of tokenization: word and sentence.']

* Use NLTK or spaCy libraries

2. Normalization: concept of taking misspelled words and converting them into their original form. This is another building block in NLP in that it helps get the text to a readable form and allows us to create other use cases on top of it.
* Stemmingremoves the suffix from a word and reduces it to its original form. This serves as a “rough” cut off the end of the word. An example of stemming might be to reduce “horses” to “horse” and “ponies” to “poni.” As seen here, the truncated form is not always a real word.

* Lemmatization: removes the suffix from a word and reduces it to its original form. Lemmatization tends to be a “smoother” cut off the end of the word. It tries to return to the original root word. In contrast to stemming, lemmatization always returns a real word. For example, the word “am” might be lemmatized to “be.” While stemming is a blunt instrument that follows abstract rules regardless of real-world usage, lemmatization performs a similar process but reduces words to their root. Lemmatization accomplishes this by using a lexicon (a specialized dictionary) of words and their variant forms.

3. Part-of-Speech Tagging: PoS tagging is the concept of finding each word's part of speech in a given document.

4. Bag-of-Words: If we create a bag-of-words (BoW) model (i.e., the most frequent words), we can build models from that. The basic idea behind this model is this: We have a document of words, but we don't care about the order of the words. We can count these words and create models based on how frequently they appear.

5. n-gram
In NLP, there is an n-gram method, which is a sequence of items from a given text. With n-gram, you create groupings of items from the text of size 1 or more. The following n-grams are common:
* Unigram is an n-gram of size 1.
* Bigram is an n-gram of size 2.
* Trigram is an n-gram of size 3.

6. Text Similarity: Another popular use case for NLP is determining document or sentence similarity. These are important use cases, because they can tell us a lot about a document and its contents.

## NLP Analyses
There are three types of NLP analyses:
1. Syntactic analysis is essentially checking the dictionary definition of each element of a sentence or document. In this type of analysis, we don't care about the words that come before or after the word in question—we just care about the given word.
2. Sentiment analysis pertains to what the text means. Is it positive, negative, or neutral? You can come up with a score of how positive or negative the text is using NLP.
3. Semantic analysis entails extracting the meaning of the text. You want to analyze the meaning of each word, and then relate that to the meaning of the text as a whole.

## Named-Entity Recognition
In NLP, named-entity recognition (NER) is the concept of taking a document and finding all of the important terms therein. By "important," we mean names of places and people, government organizations, and so forth.

## Bert NLP Primer
https://huggingface.co/blog/bert-101

## SG Learn AI
https://learn.aisingapore.org/

## Github Learning
https://lab.github.com/

## Interesting Projects
* Beginner Projects: https://www.upgrad.com/blog/data-science-project-ideas-topics-beginners/
* Weird Projects: https://www.analyticsvidhya.com/blog/2019/12/five-weird-data-science-uses/

## Development Methodology for ML
https://assaf-pinhasi.medium.com/towards-a-development-methodology-for-machine-learning-part-i-f1050a0bc607

## Data Transformation
https://towardsdatascience.com/data-transformation-and-feature-engineering-e3c7dfbb4899

## Learn Scikit

https://scikit-learn.org/stable/index.html

## Cheat Sheet of Machine Learning and Python (and Math) Cheat Sheets

https://medium.com/machine-learning-in-practice/cheat-sheet-of-machine-learning-and-python-and-math-cheat-sheets-a4afe4e791b6

## My Curated List of AI and Machine Learning Resources from Around the Web

https://medium.com/machine-learning-in-practice/my-curated-list-of-ai-and-machine-learning-resources-from-around-the-web-9a97823b8524

## 7 Classical Assumptions of Ordinary Least Squares (OLS) Linear Regression

https://statisticsbyjim.com/regression/ols-linear-regression-assumptions/

## ML MindMap 
https://whimsical.com/machine-learning-roadmap-2020-CA7f3ykvXpnJ9Az32vYXva

## The guy who made ML MindMap

https://github.com/mrdbourke

## Image Processing Lib in Python

https://neptune.ai/blog/image-processing-python-libraries-for-machine-learning
