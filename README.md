## Langchain Masterclass


### 1. Install Docker

### 2. Create a Python virtual environment

    python3 -m venv langchain_ai

    source langchain_ai/bin/activate



### 3. Run Docker compose

If you have a GPU:

    docker compose -f docker-compose-with-gpu.yml up -d

If you don't have a GPU:

    docker compose -f docker-compose-with-gpu.yml up -d


### 4. Validate servers

When clicking the links below you should see an output on the browser.

- [Ollama](http://localhost:11434)
- [MongoDB](http://localhost:27017)
- [OpenWebUI](http://localhost:8080)

### 5. Install the models

1. Open the [OpenWebUI](http://localhost:8080). 
2. Click on the profile icon on the top right and select Admin Panel
3. Select the settings tab from the top navigation bar
4. Select Models
5. In Pull a model from Ollama.com, enter model name and click on the submit button. You must download the following models:
    - llama3.2
    - nomic-embed-text
