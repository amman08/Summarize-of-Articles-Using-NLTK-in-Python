# Summarize-of-Articles-Using-NLTK-in-Python
Introduction
Text summarization is the technique for generating a concise and precise summary of voluminous texts while focusing on the sections that convey useful information, and without losing the overall meaning. Automatic text summarization aims to transform lengthy documents into shortened versions, something which could be difficult and costly to undertake if done manually. 
Machine learning algorithms can be trained to comprehend documents and identify the sections that convey important facts and information before producing the required summarized texts. For example, the image below is of this news article that has been fed into a machine learning algorithm to generate a summary.
Types of text summarization
Text summarization is mainly classified into 2 types.
1.	Extraction-based summarization
2.	Abstraction-based summarization

1.Extraction-based summarization

In extraction-based summarization, a subset of words that represent the most important points is pulled from a piece of text and combined to make a summary. 
Highlighter = Extractive-based summarization
In machine learning, extractive summarization usually involves weighing the essential sections of sentences and using the results to generate summaries. Different types of algorithms and methods can be used to find the weights of the sentences and then rank them according to their relevance and similarity with one another.

Example
TEXT: Amman and Balaji took a taxi to attend the night party in the city. While in the party, Balaji collapsed and was rushed to the hospital.

SUMMARY: Amman and Balaji attend party. Balaji rushed hospital

Extracted summary is composed of the words highlighted in bold, the results may not be grammatically accurate.

2. Abstraction-based summarization

In abstraction-based summarization, advanced deep learning techniques are applied to paraphrase and shorten the original document, just like humans do. 
Pen = Abstraction-based summarization
Since abstractive machine learning algorithms can generate new phrases and sentences that represent the most important information from the source text, they can assist in overcoming the grammatical inaccuracies of the extraction techniques. 

Example
TEXT: Amman and Balaji took a taxi to attend the night party in the city. While in the party, Balaji collapsed and was rushed to the hospital.

SUMMARY: Balaji was hospitalized after attending a party with Amman.

Abstraction performs better at text summarization, developing its algorithms requires complicated deep learning techniques and sophisticated language modelling. To generate plausible outputs, abstraction-based summarization approaches must address a wide variety of NLP problems, such as natural language generation, semantic representation, and inference permutation.


Executive Summary

Project was objectified to creating a code to Summarize of Articles in Python using NLTK certain library are imported for this project like Heapq, BS4, URLLIB Request, Regular Expressions. Using BS4 and URLLIB Request we can get data and html code from website like Investopedia, Encyclopaedia etc after getting data using regular expressions, we must clean the data once the data is cleaned using Heapq the summary will be executed.

Project is creating an app that can reads an article of text and creating a summary for that article using NLTK via Natural processing Language(NLP). Identifying the problem that humans take more time to make smart decisions. My idea is identifying the gap where humans take more time to take decision So innovatively creating an app which make smart decisions easily instead of humans in less amount of time. Consequently, developing the app increases the scale of the app and grabbing the opportunity in future so the by-product for the app is revenue.

App can be used in finance in different sectors taking the stock previous data and can know the trend, pattern and moment of the stock (investment Decisions). As an Investor while investing in a company he has to know the analysis of the company here this app will suggest weather to invest or not based on the previous data. This app can be useful to the high Networth portfolio investors like Equity Traded Funds(ETF), Mutual Funds to make easy decision in short span of time to achieve profits. So here upgrading the stock market with AI/ML technology can sustain in market for the longer period and also scalability of customers  increases for the app and finally the by-product revenue is generated.
