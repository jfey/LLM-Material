# Machine Learning, LLM, Image Recognition 

After always ending up north of 500 browser tabs open with (mostly) LLM-related content i try to migrate the links into 
this repo. This allows also for a better organisation and commentary. I try to add comments per link/topic. The content 
here is (currently) mainly used to help me to remember certain information, which i found along the way. This page focuses 
on LLM topics. Other topics are covered on dedicated pages.

## Image recognition

[image recognition.md](image%20recognition.md)


# LLM-Material

## Prompts

[Fuck You, Show Me The Prompt](https://hamel.dev/blog/posts/prompt/). In this blog post, I’ll show you how you can intercept
API calls w/prompts for any tool, without having to fumble through docs or read source code. I’ll show you how to setup and 
operate mitmproxy with examples from the LLM the tools I previously mentioned. Lots of interesting details about prompts
and ways of how to analyze whats going on.


## Vector Databases

[Brief Backgrounder](vector_database_backgrounder.md)

[Vector DB Comparison](https://vdbs.superlinked.com/) is a very handy site, listing a lot of database and comparing features.
![vectordb_comparison.png](images%2Fvectordb_comparison.png)



### Database Engines


### Libraries Used Internally

[Faiss](https://github.com/facebookresearch/faiss)


### Tools

[VectorIO](https://github.com/AI-Northstar-Tech/vector-io). This library uses a universal format for vector 
datasets to easily export and import data from all vector databases.

[VectorFlow](https://github.com/dgarnitz/vectorflow). Simple API endpoint that ingests large volumes of raw data,
processes, and stores or returns the vectors quickly and reliably

[Site](https://www.getvectorflow.com/) with docs and demo video

###  Articles

[Building Generative AI Applications Using MongoDB](https://www.mongodb.com/library/vector-search/building-generative-ai-applications-using-mongodb?xs=533003): Harnessing the Power of Atlas Vector Search and Open Source Models.
Nice intro into using MongoDB as a VectorDB. Easy to follow examples 

[Multimodal Vector-Search Using CLIP on MongoDB](https://docs.superduperdb.com/docs/use_cases/vector_search/multimodal_image_search_clip/). This notebook demonstrates how SuperDuperDB can perform multimodal searches using the VectorIndex. It highlights SuperDuperDB's flexibility in integrating different models for vectorizing 
diverse queries during search and inference. In this example, we utilize the CLIP multimodal architecture.

MongoDB joins Cassandra, PostgreSQL and SingleStore in implementing AI-friendly features
https://www.theregister.com/2023/07/11/vector_databases/
Lightweight backgrounder, mentioning MongoDB

5 Best Courses on Vector Database
https://analyticsindiamag.com/5-best-courses-on-vector-database/


### Demos/Tutorials

[Vector store and query engine for video recordings](https://github.com/daily-demos/recording-vector-store/tree/v1.0). This demo helps you build a vector database using your 
recordings using LlamaIndex and Chroma.

[Vector Search RAG Tutorial – Combine Your Data with LLMs with Advanced Search](https://www.youtube.com/watch?v=JEBDfGqrAUA). Learn how to use vector search and embeddings 
to easily combine your data with large language models like GPT-4. You will first learn the concepts 
and then create three projects.

[Zeta Alpha Trends in AI](https://www.youtube.com/@zetavector/videos). Monthly updates lasting around one hour.

