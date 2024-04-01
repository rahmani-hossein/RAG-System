# Question-Answering-form-Article
This is a quick demo for Question Answering from the Article that I chose, a famous Bitcoin paper by Satoshi Nakamoto. Here, I implemented a RAG system and a search engine Tavily as an agent to search on the Internet if your question isn't in the paper :)))

I chose the **ChatGPT4** model  and developed it with **LangChain** and **Chroma** which are really strong combinations and did great on these questions.

For an introduction to RAG, you can check [this other cookbook](https://huggingface.co/learn/cookbook/en/rag_zephyr_langchain)! Also, I would give comments about my code that I think it's helpful.

RAG systems are complex: here is a RAG diagram, where we noted in blue all possibilities for system enhancement:

<img src="https://huggingface.co/datasets/huggingface/cookbook-images/resolve/main/RAG_workflow.png" height="700">

Implementing any of these improvements can bring a huge performance boost, but changing anything is useless if you cannot monitor the impact of your changes on the system's performance! 




## Future Contributions
1. I will add some evaluation of answering quality by building a synthetic evaluation dataset and using LLM-as-a-judge to compute the accuracy of your system.

2. Add other resources and make it challenging that vector search fails and use query expansion technique and other on large scale data.


**Remark:** I want to treat this as an exercise and implement every interesting method or trick that I find helpful here to have them all in one place. Maybe some people can benefit from them. 
