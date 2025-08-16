# Ollama + WebUI one command up
This Docker Compose container bundle let you set up, a web-based ChatGPT like interface for interacting with local Ollama large language models LLMs that runs totally on your own hardware. This setup lets you easily run powerful AI large language models on your machine and chat with them through a sleek browser UI.

## Features

- Runs Ollama, a local large language model server.
- Provides a web UI to chat with Ollama models.
- Simple Docker Compose setup for quick deployment.
- Data persistence with Docker volumes.
- Auto-restart for reliable uptime.

## Requirements

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

1. Clone this repository.

2. Build the containers:
```bash
   docker-compose build --no-cache
```

3. Run the continers:
```bash
   docker-compose up
```

4. Access the Ollama container’s command line to pull a model. Available models can be found here:
https://ollama.com/search

```bash
ollama pull <modelname>
```

5. Start chatting with your Ollama language model through HolaWeb!