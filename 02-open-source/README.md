# Module 2

## ... Running Open-source LLMs in SaturnCloud ...

## Running LLMs Locally without a GPU with Ollama

Running Ollama in Docker:

```bash
docker run -it \
    -v ollama:/root/.ollama \
    -p 11434:11434 \
    --name ollama \
    ollama/ollama
```

Pull the model in Docker

```bash
docker exec -it ollama bash
ollama pull phi3
```

## Ollama + Elastic in Docker Compose

```bash
docker compose up
```

Pull the model in Docker

```bash
docker exec -it ollama bash
ollama pull phi3
```

## Creating a Streamlit UI


