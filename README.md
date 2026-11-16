# Calculator API Project

This project includes a FastAPI calculator app and a pytest suite covering unit, integration, and end-to-end behavior.

## Run the tests

From the project root:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m playwright install chromium
pytest -q
```

You can also run just a subset of tests:

```bash
pytest -q tests/unit
pytest -q tests/integration
pytest -q tests/e2e
```

## Docker image

This project is also published to Docker Hub:

https://hub.docker.com/r/choreazam/module11_is601

## Run locally with Docker

```bash
docker pull choreazam/module11_is601

docker run -p 8000:8000 choreazam/module11_is601
```

Then open:

```text
http://localhost:8000
```
- [Git Downloads](https://git-scm.com/downloads)
- [Python Downloads](https://www.python.org/downloads/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [GitHub SSH Setup Guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
