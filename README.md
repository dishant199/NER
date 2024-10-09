# Named Entity Recognition

**Background**

Natural Language Processing (NLP), an area of linguistics, computer science, and artificial intelligence, studies how computers interact with human language. The basic objective of NLP is to allow computers to effectively read, interpret, and modify human language. NLP has progressed significantly over the years, from simple rule-based algorithms to complicated machine learning and deep learning models.
Named Entity Recognition (NER) has developed as a critical component in NLP, owing to the rising requirement to extract meaningful information from the massive volumes of unstructured text data created every day. NER entails detecting and categorizing significant components in text into specified groups, such as the names of individuals, organizations, locations, time expressions, and numerical values such as dates and sums. This capacity is critical for a wide range of applications, including information.

**Business Problem**

The exponential growth of data in the digital age has resulted in an ever-increasing volume of unstructured textual information. From social media posts and online publications to company reports and email conversations, the digital environment is teeming with complicated and sometimes confusing information. The capacity to filter through this flood and retrieve essential information quickly and accurately has become critical in the middle of this rush. Nonetheless, companies and organizations continue to face the problem of extracting relevant information from these disparate textual sources.


**Data Used**

Data set overview

NER Corpus Dataset Description
The Kaggle-sourced NER Corpus dataset serves as the foundation for training and assessing the proposed Named Entity Recognition (NER) system. This structured dataset is made up of four essential columns:
•
Sentence Number: Each item is assigned a unique sentence number, allowing for the systematic organization and reference of individual sentences within the corpus.
•
Sentence: The textual content is encapsulated in the 'Sentence' column, which represents the unstructured text input on which the NER model will be trained. This column serves as the system's major input feature.
•
Parts of Speech (POS): This column indicates the grammatical category of each word in the related phrase. Parts of speech are important in comprehending the syntactic structure of sentences and in extracting meaningful items.
•
Tags: The named entities within each sentence are listed in the 'Tags' column. Geographical entities (geo), organizations (org), persons (per), geopolitical entities (gpe), time indicators (tim), artifacts (art), events (eve), and natural phenomena (nat) are among the tags assigned to these entities. This column is used as the basis for training the NER model.
The collection contains a wide range of textual data, including variations in sentence structure
