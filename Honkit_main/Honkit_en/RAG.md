# Improving Answer Accuracy with RAG

## What is RAG
Retrieval-Augmented Generation (RAG) is a technique that combines text generation by large language models (LLMs) with external information retrieval to suppress the generation of information not based on facts and improve the accuracy of AI responses.<br>

![RAG_01.png](/img/RAG_01.png)<br>

Due to the token limit of ChatGPT, a large number of documents cannot be supplied as-is.
Therefore, prior information retrieval using RAG is performed in ailia DX Insight, and answers are generated based on a part of that information.<br>

![RAG_02.png](/img/RAG_02.png)<br>

## About Max Token Length

`chatgpt-3.5 : 2k`<br>
`chatgpt-3.5-turbo (integrated with 16k）：16k`<br>
`chatgpt-4 : 8k`<br>
`chatgpt-4-turbo : 128k`<br>

The more tokens, the more information chunks can be fed together, improving accuracy. However, responses become slower, and costs increase accordingly.

## RAG Settings
1. In the initial screen of ailia DX insight, click the gear icon in the upper right to display the settings window.<br>
![setup_03.png](/img/setup_03.png)<br>
1. Select "RAG" from the items on the left.<br>
![RAG_03.png](/img/RAG_03.png)
1. You can set rerank and TOPK.

<br>

#### [Next&emsp;＞](Embedding.md)