# Push-Solar-10.7B-to-Ollama-Hub

Steps to host your LLM in Ollama model hub:

1. Download the model GGUF from Huggingface and prepare the `Modelfile`.
2. Go to https://ollama.com/new to create a new model. Once you give a name to the model, instructions will be mentioned on how to push your model to Ollama.
3. `ollama create kristada673/solar-10.7b-instruct-v1.0-uncensored -f ./Modelfile`
4. `ollama push kristada673/solar-10.7b-instruct-v1.0-uncensored`
