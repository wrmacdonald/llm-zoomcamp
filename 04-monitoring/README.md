# Module 4

## Setup Streamlit app with User Feedback

Start the containers

```bash
cd 04-monitoring/app
docker compose up
```

Pull the model in ollama container

```bash
docker exec -it ollama bash
ollama pull phi3
```

Index the data in elasticsearch container

```bash
python prep.py
```

Streamlit app can be found [here](http://localhost:8501/):



## Setup Grafana for Monitoring


