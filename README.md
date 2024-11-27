## Analysis of Parameters Indicating a Loan Default for Lending Club


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Implement a question answering assistant using LlamaIndex and OpenAI GPT models. This assistant will answer questions related to a specific set of documents and provide the location of its sources.
### Project Set up
Only two things are required to run this code:
1. Set the OpenAI API key. Change the following line to point to the folder where you have the OpenAI API Key file.
filepath = "D:\\ML\\code\\"
2. Set the path to the folder contaning the PDF insurance policy files. 
input_dir =  "D:\\ML\\data\\policy\\"
# Let us take input from a directory
### Business Obejective
The goal of the project will be to build a robust generative search system capable of effectively and accurately answering questions from various policy documents. 
### Dataset
7 pdf documents are available: The pdf files range from 15 to 44 pages. The policy documents in pdf format are the source of truth. This policy documents need to be processed, cleaned and chunked for embeddings. 
## Components of LlamaIndex
Documents: These are the "books" in your library.
2. Index: It's the "library" of your data - Stores your data.
3. Retriever: It's the "librarian" that finds relevant data - Finds data.
4. Response Synthesizer: It's the "storyteller" that creates a response - Makes responses.
5. QueryEngine: It's the "director" that makes everything work together - Coordinates everything.


## Technologies Used
- Python 3.11.1
- Pandas 2.1.4
- LlamaIndex
- OpenAI API

## Acknowledgements
This project was inspired by live session of upGrad on EDA.
UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Contact
Created by [@anilabh]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
