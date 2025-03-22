# Start-up

```bash
docker compose up
```


# Agent setup
First, after going through the first time registration, pick the AI agent example.

Then, delete the default OpenAI connection, press the '+' and pick Ollama
![step 1](images/step_1.JPG)

Double click on the Ollama node and configure the base URL with llm-server:11434 (internal docker connection)
![step 2](images/step_2.JPG)

Set the model to llama2:latest. If you wanted a different model, you need to change the model name in the ```ollama pull <model-name>``` part of ```DockerfileServer```
![step 3](images/step_3.JPG)

Try chatting!
![step 4](images/step_4.JPG)