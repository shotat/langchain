# Interacting with APIs

> [Conceptual Guide](https://docs.langchain.com/docs/use-cases/apis)


Lots of data and information is stored behind APIs.
This page covers all resources available in LangChain for working with APIs.

## Chains

If you are just getting started, and you have relatively apis, you should get started with chains.
Chains are a sequence of predetermined steps, so they are good to get started with as they give you more control and let you 
understand what is happening better.

- [API Chain](../modules/chains/examples/api.ipynb)

## Agents

Agents are more complex, and involve multiple queries to the LLM to understand what to do.
The downside of agents are that you have less control. The upside is that they are more powerful,
which allows you to use them on larger and more complex schemas. 

- [OpenAPI Agent](../modules/agents/toolkits/examples/openapi.ipynb)
