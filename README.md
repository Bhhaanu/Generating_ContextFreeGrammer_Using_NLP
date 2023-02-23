# Generating_ContextFreeGrammer_Using_NLP


The following objectives are covered in the notebook:

Objective 1
Write separate python functions which accept a string and a number ‘n’ and return the following:

a.	N most frequent Nouns  
Take the function name as “GetNMostFrequentNouns”

b.	N most frequent Verbs
Take the function name as “GetNMostFrequentVerbs”

c.	N most frequent Delimiters
Take the function name as “GetNMostFrequentDelimiters”

d.	N most frequent Prepositions
Take the function name as “GetNMostFrequentPrepositions”

Objective 2

Write a python function that accepts a string and prints the first sentence in the string along with its syntax tree.
take the function name “PrintSyntaxTrees”.

Objective 3

Write python functions that accept a string and return the following using regular expressions: 

a.	Text from the string after removing all the punctuations 
take function name as “TextAfterRemovingPunctuations”

b.	Text from the string after removing all the numbers/digits 
take function name as “TextAfterRemovingDigits”

c.	All the words which begin with the capital letter 
take function name as “AllCapitalizedWordsFromText”

d.	All the emails from the string
take the function name “AllEmailsFromText.”

Objective 4

4.	Write python functions that accept a string as an input and return the following chunks.

a.	Phrases having Proper nouns followed by Verbs
take function name as “ChunkingVer1”

b.	Verb Phrases having Verbs followed by Adjectives
take function name as “ChunkingVer2”

c.	Noun Phrases having Determiners followed by Nouns
take function name as “ChunkingVer3”

d.	Verb Phrases having Verbs followed by Adverbs
Take the function name as “ChunkingVer4”

e.	Phrases having Delimiter, Adjectives, and Nouns in the respective order
take function name as “ChunkingVer5”

f.	Noun Phrases having Nouns and Adjectives, terminated with Nouns
take function name as “ChunkingVer6.”

Objective 5

5.	Make a content-free grammar having the following rules: 

a.	Noun Phrases are followed by Verb Phrases

b.	Verb Phrase can have 
i.	Verb and noun phrase 
ii.	Verb, noun phrase, and a preposition

c.	Noun Phrases can have 
i.	Delimiters followed by a noun 
ii.	Delimiters, nouns, and preposition phrases,

d.	Preposition phrases have a preposition followed by a noun phrase
e. The delimiters, verbs, prepositions, and nouns for the grammar should be the two most frequent words of each type from “FIFAWorldCup2018.txt”
 Generate the CFG for the “FIFAWorldCup2018.txt” file and save them in a file named “CFG.txt”

