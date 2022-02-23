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

