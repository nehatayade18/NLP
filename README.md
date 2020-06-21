# NLP
Classification/Topic Modeling/Vectorixation

## Text Cleaning and Pre-processing
In NLP, text and documents contain many words that are redundant for text classification, such as stopwords, mis-spellings, slangs, and etc. In many algorithms like statistical and probabilistic learning methods, noise and unnecessary features can negatively affect the overall performance. So, the elimination of these features is extremely important.

Methods:
* Tokenization-
Process of breaking down a stream of text into words, phrases, symbols, or any other meaningful elements called tokens. The main goal of this step is to extract individual words in a sentence. 

* Stopwords:
Text and document classification over social media, such as Twitter, Facebook, and so on is usually affected by the noisy nature (abbreviations, irregular forms) of the text corpora.

* Capitalization:
Sentences can contain a mixture of uppercase and lower case letters. Multiple sentences make up a text document. To reduce the problem space, the most common approach is to reduce everything to lower case. This brings all words in a document in same space, but it often changes the meaning of some words.

*Slangs and Abbreviations:
Slangs and abbreviations can cause problems while executing the pre-processing steps. An abbreviation is a shortened form of a word, such as SVM stand for Support Vector Machine. Common method to deal with these words is converting them to formal language.

*Noise Removal:
Text documents generally contains characters like punctuations or special characters and they are not necessary for text mining or classification purposes. 

*Spelling Correction
Different techniques, such as hashing-based and context-sensitive spelling correction techniques, or spelling correction using trie and damerau-levenshtein distance bigram have been introduced to tackle this issue.

*Lemmatization
Text lemmatization is the process of eliminating redundant prefix or suffix of a word and extract the base word (lemma).

*Stemming
Text Stemming is modifying a word to obtain its variants using different linguistic processes like affixation (addition of affixes). For example, the stem of the word “studying” is “study”, to which -ing.

