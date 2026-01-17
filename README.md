# spring-ai-ollama



# 🚀 Quick Start

## 1️⃣ Start Ollama Service

```bash
docker compose -f docker-compose.yml up
````

Starts the Ollama container using Docker Compose.
Keep this terminal running.

---

## 2️⃣ Run AI Model

```bash
docker exec -it ollama ollama run llama3.2:1b
```

Runs the LLaMA 3.2 (1B) model inside the container.
The model will download automatically on first run.

---

```


