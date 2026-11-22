# GenAI Platform — RAG + Agent System (12-Step Capstone)

A cumulative, from-scratch build of a production-shaped Retrieval-Augmented Generation and Agent platform, ending in a concurrent FastAPI service with SSE token streaming.

## Quick Start
```bash
cp .env.example .env
python3.12 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
export PYTHONPATH=src
pytest -q
```
