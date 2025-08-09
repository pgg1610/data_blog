---
categories:
- chemical-science
- machine-learning
- resources
- AI
date: '2024-05-01'
description: Resources around LLM development and research 
layout: post
title: Large Language Models
toc: true
---

How LLMs benefit modeling processes:
1. Low data modeling
2. Fewer (one model) to predict multiple end points across different modalities (sentiment, regression, classification, text completion)
3. Rich embeddings generated for unstructured data sets - useful for recommenders | similarity search
4. Quick prototyping - LLMs based workflow can increase the pace at which we code, search, train models

General areas:  
1) Predictive modeling
2) Automation and novel human-machine interaction
3) Knowledge extraction and translation
4) Education (lowering entry barrier)
## Applications
### Chemistry 
- [[Autonomous chemical research with large language models]]
- [Chemcrow](https://arxiv.org/abs/2304.05376)
- [Is GPT-3 all you need?](https://chemrxiv.org/engage/chemrxiv/article-details/63eb5a669da0bc6b33e97a35](https://chemrxiv.org/engage/chemrxiv/article-details/63eb5a669da0bc6b33e97a35)[Nature Paper](https://www.nature.com/articles/s42256-023-00788-1)
- [Catalyst Property Prediction with CatBERTa: Unveiling Feature Exploration Strategies through Large Language Models](https://pubs.acs.org/doi/10.1021/acscatal.3c04956)
* [Chemistry reaction entity extraction](https://github.com/qai222/LLM_organic_synthesis#extracting-structured-data-from-free-form-organic-synthesis-text)
* [[Multi-modal molecule structure–text model for text-based retrieval and editing]]
* [Are large language models superhuman chemists?](https://arxiv.org/pdf/2404.01475.pdf)


## Prompt engineering

Prompt blog:
[https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/#external-apis](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/#external-apis)

Prompts are tiny programs [Inspiration](https://twitter.com/balajis/status/1750086314928873865)
> Prompt engineering is a subset of software engineering

PromptBase : 
https://github.com/microsoft/promptbase
>> Medicine related prompts 

OpenAI Prompt Engineering : 
https://platform.openai.com/docs/guides/prompt-engineering/prompt-engineering

## Chains

Pre-determined set of steps to undertake a task 
This is first step in creating a platform 

### RAGs

RAG for LLMs - A Survey :
https://arxiv.org/abs/2312.10997

Deconstructing RAG
[https://twitter.com/RLanceMartin/status/1727019896394207624](https://twitter.com/RLanceMartin/status/1727019896394207624)

It can be hard to follow all of the RAG strategies that have come out over the past months.

I created a few guides to organize them into major themes and show how to build multi-modal / semi-structured RAG on complex docs (w/ images, tables).

Here's a few of the major themes:

1. Query Transformations - User questions may not be well-posed / -worded for retrieval. There's a host of methods that re-write and / or expand (fan-out into multiple sub-questions) questions that maximize the chance of retrieving relevant documents. See blog: [https://blog.langchain.dev/query-transformations/](https://blog.langchain.dev/query-transformations/)

2. Routing - Queries may need to be routed to different data sources depending on what is being asked. Recent blog reviewing OpenAI's RAG strategies provides some guidance on question routing: [https://blog.langchain.dev/applying-openai-rag/](https://blog.langchain.dev/applying-openai-rag/)

3. Query Construction - To access structured data, natural language needs to be converted into specific a query syntax. Various approaches can access data in SQL, SQL w/ semantic columns (pgvector), graph DBs, vectorDB w/ metadata filters, etc. See blog: [https://blog.langchain.dev/query-construction/](https://blog.langchain.dev/query-construction/)

4. Index Building - One of the most useful tricks I've been using is multi-representation indexing: decouple what you index for retrieval (e.g., table or image summary) from what you pass to the llm for answer synthesis (e.g., the raw image, a table). See blog:

[https://blog.langchain.dev/semi-structured-multi-modal-rag/](https://blog.langchain.dev/semi-structured-multi-modal-rag/)

4a. Multi-Modal -

This cookbook show how I used this approach for RAG on a substack (

@jaminball

's Clouded Judgement) that has many images of densely packed tables, graphs:

[https://github.com/langchain-ai/langchain/blob/master/cookbook/Multi_modal_RAG.ipynb](https://github.com/langchain-ai/langchain/blob/master/cookbook/Multi_modal_RAG.ipynb)

4b. Semi-Structured -

This cookbook show how I used this for RAG on a docs (papers) with tables, which can be split using naive RAG text-splitting (that does not explicitly preserve them):

[https://github.com/langchain-ai/langchain/blob/master/cookbook/Semi_Structured_RAG.ipynb](https://github.com/langchain-ai/langchain/blob/master/cookbook/Semi_Structured_RAG.ipynb)

5. Post-processing - Given retrieved documents, there are various way to rank / filter them. Recent blog reviewing OpenAI's RAG strategies provides a few ideas on applying post-processing: [https://blog.langchain.dev/applying-openai-rag/](https://blog.langchain.dev/applying-openai-rag/)

Self-querying to work with meta data in the document chunks :[https://python.langchain.com/docs/modules/data_connection/retrievers/self_query](https://python.langchain.com/docs/modules/data_connection/retrievers/self_query)

Knowledge graph data :
[https://www.youtube.com/watch?v=nPG_jKrSpi0&t=11s](https://www.youtube.com/watch?v=nPG_jKrSpi0&t=11s)

OpenAI recipe for graphDB implementation : 
https://github.com/openai/openai-cookbook/blob/main/examples/RAG_with_graph_db.ipynb


## [[Agents]]

Hitchhiker's Guide  from Chain-of-Thought reasoning to Language Agents: https://arxiv.org/pdf/2311.11797.pdf

Non-structured ways to do task by giving central model access to tools - 
Different orchestration platforms : 
1) https://github.com/guidance-ai/guidance
2) Semantic kernel 
3) Langchain 
4) Autogen 

Medium open solution from. companies : crew.ai 

Agent on MineCraft : Voyager / MineDojo 

Agents with API : Gorilla 

AutoGen with Semantic Kernel : https://github.com/microsoft/semantic-kernel/blob/sk-autogen/python/notebooks/12-sk-autogen-agents.ipynb

### AutoGen vs Semantic Kernel : 
  
Autogen is a framework for letting multiple agents collaborate with each other to complete a request. Semantic Kernel, on the other hand, is an SDK that helps you give a single agent a set of tools (via plugins). Because of this, we believe both projects complement each other. To make a team of agents in Autogen productive, you’ll ultimately want to give them plugins so they can complete real work. This is when you’d want to use the two projects together.

Put more simply…  
– Need agents to collaborate with each other? Use agents.  
– Need agents to do work with tools (i.e., plugins)? Use Semantic Kernel.  
– Need agents to collaborate with each other with tools? Use both!

**How does LLM use the function/tool ?**

We pass the parameters in term of json or protobuf with function name, description, params 

The LLM doesnt call the function for us - it JUST tells us with the known information what would be the function we NEED to call 
Not every time we would get a json output so we need safeguards for it. 

`functions` and `function_calls` are accounted in the tokens 

Gorilla : [https://gorilla.cs.berkeley.edu/](https://gorilla.cs.berkeley.edu/ "https://gorilla.cs.berkeley.edu/")

Solutions from external companies : 
https://www.lindy.ai/
crew.ai 

LLM powered autonomous agents :

[https://lilianweng.github.io/posts/2023-06-23-agent/?utm_source=pocket_saves](https://lilianweng.github.io/posts/2023-06-23-agent/?utm_source=pocket_saves)

[https://peterroelants.github.io/posts/react-repl-agent/](https://peterroelants.github.io/posts/react-repl-agent/)

Python REPL agent:[https://python.langchain.com/docs/integrations/toolkits/python](https://python.langchain.com/docs/integrations/toolkits/python)

Robust MRKL:  
[https://github.com/whitead/robust-mrkl/tree/main](https://github.com/whitead/robust-mrkl/tree/main)

Microsoft Autogen : 
https://github.com/microsoft/semantic-kernel/blob/sk-autogen/python/notebooks/12-sk-autogen-agents.ipynb
https://microsoft.github.io/autogen/docs/Use-Cases/agent_chat/#diverse-applications-implemented-with-autogen

OpenAI's Assistant API vs Langchain Agent : https://blog.langchain.dev/openais-bet-on-a-cognitive-architecture/

## Evaluations 
1) Regas
2) PromptFlow
3) StaRK from James Zou lab: https://arxiv.org/abs/2404.13207

Andrej Karpathy : 
https://nicholas.carlini.com/writing/2024/my-benchmark-for-large-language-models.html

## Training 
1) RLHF 
2) [[DPO]]

# Applications 

LLM Chatbot to converse and answer domain specific questions (think of NPA-space) by providing library and digest the literature

LLM prediction benchmarking with other model we have in-house
How can we more 10x more or 10x better?

>> Knowledge base for conversing in domain-specific fashion for latest information

### Machine translation 
>> NLP substructure queries ---> Protobuf substructure script ---> Search in the dataset 
