# Anote_Q-A
 
# Project Overview 

The Anote Q-A project is driven by the goal of understanding the baseline performance and accuracy of question-answering capabilities in cutting-edge models such as GPT-3.5 Turbo, GPT4All, Claude, and LLAMA-2. Our commitment lies in pushing the boundaries of their capabilities and significantly enhancing their accuracy. 






## GPT 3.5 Turbo 


## GPT4ALL 


## Claude 


## LLAMA-2


# Datasets 
For fine-tuning and testing, we utilized two question-answering datasets. FinanceBench is a novel benchmark
developed by Patronus AI for evaluating the performance of LLMs on open-book financial question
answering. The dataset is comprised of 10,231 questions about publicly traded companies. Each question
is accompanied by corresponding answers and evidence strings. It covers 40 companies in the USA,
spanning 361 public filings, including 10Ks, 10Qs, 8Ks, and Earnings Reports, released between 2015 and
2023. A typical entry contains the question (e.g., “What Was AMCOR’s Adjusted Non-GAAP EBITDA
for FY 2023”), the answer (e.g., “AMCOR’s Adj. EBITDA was 2,018 million USD in FY 2023”), an evidence
string (containing information needed to verify the answer), and a page number from the relevant
document. The second dataset is RAG Instruct Benchmark tester, designed by LLMWARE to measure
the different capabilities of retrieval augmented generation in financial and legal enterprise use cases.
The dataset includes 200 questions with context passages pulled from common ’retrieval scenarios’, e.g.,
financial news, earnings releases, contracts, invoices, technical articles, general news and short texts. The
questions, spanning Core Q&A Evaluation, Not Found Classification, Boolean - Yes/No, Math, Complex
Q&A and Summary categories, are strategically segmented to assess the capabilities of LLMs.



