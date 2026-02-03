# AI-Learning Platform
[![Documentation Status](https://readthedocs.org/projects/ai-learning-platform/badge/?version=latest)](https://ai-learning-platform.readthedocs.io/en/latest/?badge=latest)
[![React.js Build and Release](https://github.com/NavinKumarMNK/AI-Learning-Platform/actions/workflows/front-end-release.yml/badge.svg)](https://github.com/NavinKumarMNK/AI-Learning-Platform/actions/workflows/front-end-release.yml)

![Project Image](/assets/project.png)

## About
An intelligent learning platform powered by large language models and vector embeddings. The platform provides personalized AI-driven educational content with document processing capabilities and semantic search.

## Tech Stack
- **Frontend**: React, TypeScript, Vite
- **Backend**: Django, Django REST Framework, PostgreSQL, Cassandra
- **ML Service**: Ray Serve, vLLM, Qdrant (Vector DB)
- **Infrastructure**: Docker, Docker Swarm

# Documentation 
- This project uses `mkdocs` as the documentation service
- serve the document 

```bash
pip install mkdocs
pip install markdown-include
pip install mkdocstrings
mkdocs serve -a localhost:8001
```
