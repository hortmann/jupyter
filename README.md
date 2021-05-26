# jupyter

Here are some trials for essential NLP process steps.
I used 2 textfiles for most of the trials - SEMP1 (job description) and JON (Resume)
Mostly they are loaded into the Notebooks as TXT and the preprocessed ( cleaned, tokenized ,etc)

The trials are covering 3 areas of NLP we would utilze in Resprime:

a) preprocessing, indexing ant cross-referencing the documents and finding matchings on word-level (1:1 or word similarities)
b) Using BERT transformers for paraphrasing and sentence/document level similarity
c) using BERTopic for Topic-Modeling 

In general we can bring every output of the functions into fileformat (Excel, JSON)
Some functions do that as ashow case

My approach would be:
- Finding Topics in the documents, where the topic model is finetuned to the topics we need
- find words around these topics to prime
- give other information to better match the documents ( like intensifying text in a topic etc) 
  
