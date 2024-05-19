#Querying PDF With Astra and LangChain

### A question-answering demo using Astra DB and LangChain, powered by Vector Search

#### Pre-requisites:

You need a **_Serverless Cassandra with Vector Search_** database on [Astra DB](https://astra.datastax.com) to run this demo. As outlined in more detail [here](https://docs.datastax.com/en/astra-serverless/docs/vector-search/quickstart.html#_prepare_for_using_your_vector_database), you should get a DB Token with role _Database Administrator_ and copy your Database ID: these connection parameters are needed momentarily.

You also need an [OpenAI API Key](https://cassio.org/start_here/#llm-access) for this demo to work.

#### What you will do:

- Setup: import dependencies, provide secrets, create the LangChain vector store;
- Run a Question-Answering loop retrieving the relevant headlines and having an LLM construct the answer.
