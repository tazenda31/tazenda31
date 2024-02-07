# Nominal phrases
Our goal today is to perform a simple linguistic analysis – finding nominal phrases in a text and analysing their structure.

### Introduction for engineers and other non-linguists
Nominal phrases are, along with verbal phrases and some other smaller elements, fundamental building blocks of sentences. As they carry some morphological elements that help syntactical combinatorics, they may be interpreted as morphosyntactic elements. A nominal phrase consists of a nominal element (a noun or a pronoun) along with everything that depends on it. The main nominal element in a nominal phrase is usually called the *head*.

In the phrase _The little shop of horrors_ there are two nouns: _shop_ and _horrors_.  First, we want to know which of the two is the head of the phrase. We can do it in following manner: First, we put the phrase in a sentence:  _The little shop of horrors is a movie._ Then we try to omit one noun or the other and watch if the sentence still functions:

_The shop is a movie._

_*The horrors is a movie._ 

The first sentence, although it lacks important semantic information, is still grammatically correct. The second one is not. Therefore, we conclude that the noun _shop_ is the head of the phrase.

Furthermore, everything that describes the head in any way belongs into the same nominal phrase: _The… shop_, _little shop_, _shop of horrors_. Some of these elements depend directly on the head, others depend on the elements that themselves depend on the head.

Sometimes we make drawings of phrases, or whole sentences, to better understand the structure.

### Why would we want to know the structure of nominal phrases in language data?

1. *Understanding Structure*: Nominal phrases are key building blocks in sentences, helping establish their structure and how different parts relate to each other. Sometimes the meaning of a phrase or a sentence is so complex, that we need to analyse it to be able to understand it.
2. *Identifying Parts of Speech*: By looking at morphosyntactic features, we can figure out the roles of words within nominal phrases, which is crucial for tasks like syntactic parsing and semantic analysis in NLP.
3. *Extracting Meaning*: Analysing these features helps us uncover the meaning conveyed by nominal phrases, showing us how words interact and contribute to the overall message.
4. *Language Learning and Teaching*: Studying nominal phrases aids in language learning and teaching, giving learners insight into how words come together to form meaningful expressions. Every student of a modern foreign language knows this well.
5. *NLP Applications*: Morphosyntactic analysis is essential in NLP for tasks such as tagging parts of speech, recognizing named entities, and understanding sentiment. This analysis provides valuable data for training NLP models.
6. *Stylistic and Literary Analysis*: In literary texts, examining these features helps uncover patterns, themes, and stylistic devices used by authors, enriching literary analysis. Additionally, if we understand stylistic habits of an author, it can be one of the parts of their stylistic signature, helpful for contributing the authorship.

In summary, analysing morphosyntactic features of nominal phrases enhances our understanding of language structure and meaning, benefiting various fields such as NLP, linguistic data analysis, language learning, and literary analysis.

### Analysis
The package we will be using for linguistic analysis is [spaCy](https://spacy.io) - an open-source software library for advanced natural language processing.
