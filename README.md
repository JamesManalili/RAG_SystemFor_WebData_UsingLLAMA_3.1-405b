# <a id='toc1_'></a>[RAG system for web data using Llama 3.1-405b](#toc0_)

### **Imagine you have several web pages, and want to extract information from them. You could read each page and take notes, but that would be time-consuming. Instead, you can use a RAG system to help you. RAG systems combine the power of a large language model (LLM) with a retrieval system to provide context to the LLM. This allows you to ask questions about the content of the web pages and get answers quickly.**

## <a id='toc1_5_'></a>[Setup](#toc0_)
This project need to use the following libraries:


*   [`langchain`](https://pypi.org/project/langchain/): Building applications with LLMs through composability.
*   [`ibm-watsonx-ai`](https://pypi.org/project/ibm-watsonx-ai/): `ibm-watsonx-ai` is a library that allows to work with watsonx.ai service on IBM Cloud and IBM Cloud for Data. Train, test, and deploy your models as APIs for application development and share with colleagues using this python library.
*   [`langchain-ibm`](https://pypi.org/project/langchain-ibm/): This package provides the integration between LangChain and IBM watsonx.ai through the ibm-watsonx-ai SDK.
*   [`unstructured`](https://pypi.org/project/unstructured/): A library that prepares raw documents for downstream ML tasks.
*   [`ibm-watson-machine-learning`](https://pypi.org/project/ibm-watson-machine-learning/): A library that allows to work with Watson Machine Learning service on IBM Cloud and IBM Cloud for Data. Train, test, and deploy your models as APIs for application development and share with colleagues using this python library.
