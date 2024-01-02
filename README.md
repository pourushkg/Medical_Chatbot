# Medical_Chatbot

## Steps to run the project 

### 1. Clone the repository

```bash
Project repo: https://github.com/pourushkg/Medical_Chatbot.git 
```
### 2. Create a new environment name medical_chatbot by using python=3.8

```bash
conda create -n medical_chatbot python=3.8 -y
```
### 3. Activate the new repository name medical_chatbot

```bash
conda activate medical_chatbot
```
### 4. Command to install the requirements

```bash
pip install -r requirements.txt
```

### 5. Create a .env file in the root directory and add your Pinecone credentials as follows:

```bash 
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### 6. Download the quantize model from the link provided in model folder & keep the model in the model directory:

```bash
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now, 
open up localhost:

Techstack Used:
Python
LangChain
Flask
Meta Llama2
Pinecone

