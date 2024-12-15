# PetroRAG
**Retrieval Augmented Generation (RAG) application in energy**

First of all is RAG-LLM, then I will do some experiments with NLP and Knowledge Graph. Just want to do something fun with GenAI

## RAG with OpenAI 

Here, for example, a user comes to us and has few reports in his database and he wants to quickly perform a query to get information from the reports.

I use 3 reports from the public Volve dataset; discovery report, completion report, and drilling report of well 15/9-F-15 A. 

![image](https://github.com/user-attachments/assets/a00c32fd-7441-4de0-8f32-a2a3bbc3c445)

## RAG with ColPali and Qwen2

While OpenAI is costly, I use an open source ColPali model (by Illuin Technology) and Qwen2 model (by Alibaba Group) to build a multimodal RAG that can understand reports with charts and tables. 

![image](https://github.com/user-attachments/assets/38d685f2-c782-42e2-80cd-4d2d85956dd0)


## Open for contribution/collaboration

There are several challenges that I want to address:
* Most legacy reports are scanned so it has the format of picture. How can we effectively apply OCR?
* Reports have charts, tables, or even equations. How can we use multimodal LLM to understand these information?
* Company reports are highly confidential. How can we use open-source alternatives of OpenAI models to store RAG privately? How are cost compared from one model to another?
* How can we use knowledge graph from reports to help us summarize and find connections between reports?
* Embedding vectors are huge and need storage as there are a lot of reports. How can we use different vector databases and scale up with hundreds or thousands of reports?

Open for collaboration, if anyone has ideas on this :)
