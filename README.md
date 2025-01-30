# rr_genai_projects
For GenAI projects

This repository consists of following projects:

<b>1. RAG: Retrieval Augmented Generation.  This folder consists of following notebook files:</b>

   * rag_main.ipynb: Main RAG notebook.  This file shows code base for the following components:

        a) RAG (Naive) pipeline
     
        b) Advanced RAG pipeline

        c) RAG Index persistence in ChromaDB

        d) Technique to extract citation, along with metadata and node details

   * rag_metrics.ipynb: Show how to measure accuracy of RAG retrieval.  Here, we use Relevancy metric

   * rag_hybrid_query.ipynb: Show how to implement hybrid search (vector and keyword searches) using Llamaindex

The RAG folder consists of requirements.txt - list of Python packages required to run the code.  You can install these libraries using: `pip install`

<b>NOT COVERED:<b> This RAG project does not cover implementation of DOCLING.  My reading shows DOCLING is more versatile than LlamaIndex data source: SimpleDirectoryReader. I will cover `docling` implementation in the future release. 

<br />
<b>AI-Agents:</b> WIP.............
