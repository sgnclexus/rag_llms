# Retreive info for an specific question

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [References](#references)


## About <a name = "about"></a>

Example to obtain info from pdf files using RAG (Retrieval Augmented Generation) for Large Language models (LLMs). The idea is to have a knowledge base to ask specific questions and receive accertive answers

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Installing

First of all, you need to create a working project. Second we create a virtual environment, then we activate this venv

```
(base)  ~/Documents/Desarrollos  mkdir rag_llms
(base)  ~/Documents/Desarrollos  cd rag_llms
(base)  ~/Documents/Desarrollos/rag_llms  python3 -m venv myenv
(base)  ~/Documents/Desarrollos/rag_llms  source myenv/bin/activate
```

A very important point, is that you need to have an openai account to implement llm, otherwise you cannot use it for this project

https://platform.openai.com/docs/overview


A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

```
until finished
```

Then use this like reference:

[Understand chuncks and overlap](https://github.com/FullStackRetrieval-com/RetrievalTutorials/blob/main/tutorials/LevelsOfTextSplitting/5_Levels_Of_Text_Splitting.ipynb)

End with an example of getting some data out of the system or using it for a little demo.

## References <a name = "reference"></a>

This example is based on structured-rag-pdf by thu-vu92
