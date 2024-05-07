# This is a repository for the course project submission of DA624 NLP with LLM course, dated 7.5.2024.
## Project Name
### Retrieval Augmented Generation for QA Tasks
## Team Members
- Teiboklang Chyne, 234156019
- Vaibhav Dewangan, 234156020
- Neeraj Kumar, 234156014

## Project Overview
To optimize RAG models, we investigate the impact of chunk size, embeddings, and re-ranking strategies. Through extensive QA task experimentation on Language Models, we aim to evaluate RAG performance while varying these parameters. Our objective is to discern the parameters' influence and uncover strategies for bolstering RAG's QA capabilities.

### Data
For our dataset, we used six books that focus on wealth, wisdom, and enlightenment: "Learn to Earn" by Peter Lynch and John Rothchild, "The Education of a Value Investor" by Guy Spier, "Rich Dad Poor Dad" by Robert T. Kiyosaki, "The Psychology of Money" by Morgan Housel, "The Total Money Makeover" by Dave Ramsey, and "The Millionaire Next Door" by Thomas J. Stanley. These are located as pdf in the books folder.

## Setup
### Tokens and API key:
- Please get token from HuggingFace from https://huggingface.co/docs/hub/security-tokens
- Please get API key from OpenAI, https://openai.com/index/openai-api
  
### Upload folders to Google Drive:
- Download data folder
- Upload to your Google Drive in the location MyDrive/content/ (after upload, the folder location should be MyDrive/content/data)
  
### Setup Google Colab:
- Download RAG_QA.ipynb
- Upload it as a new notebook to google colab.
- Download Results.ipynb
- Upload it as a new notebook to google colab.

## Running
### Google Drive Setup :
- Run the first cell in RAG_QA.ipynb
- It will ask for permission for access to your google drive account
- Please allow access to view files and folders
  
### Token and API key :
- In the second cell of RAG_QA.ipynb
- Please fill the variable names HF_TOKEN = "Your HuggingFace Token" and OPENAI_API_KEY = "Your Open AI API key" with your own token and api key.

### Run the cells :
That is all. You can now run all the remaining cells to generate your results.

### Evaluating results :
- Upon executing the RAG_QA, the results will be written in to MyDrive/content/data/average_scores.json
- To get the results
- Run the first cell of Results.ipynb and allow google drive access
- Run the remaining cells to get the results displayed.

### All done!



  
