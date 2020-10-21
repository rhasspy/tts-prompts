# Text to Speech Prompts

Phonetically balanced sentences (prompts) for training a text to speech system.

## Dutch

[Prompts](nl-nl/prompts.txt)

Text sources:

* [Oscar Corpus](https://oscar-corpus.com/)

Settings:

* Minimum of 3 words, maximum of 15 words
* At least 5 examples of each diphoneme
* Filter regular expressions
    * `.+@.+` - remove e-mail addresses
    * `.*http.*` - remove URLs
    * `.*\d.*` - remove numbers

## German

[Prompts](de/prompts.txt)

Text sources:

* Grimm's fairy tales
* [Common Voice sentences](https://github.com/mozilla/common-voice/tree/master/server/data/de)
