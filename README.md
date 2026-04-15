# Flask App with Docker and Argo CD

This is a simple Flask application deployed using Docker and Argo CD.

## Structure

- `src/app.py`: Main Flask application
- `requirements.txt`: Python dependencies
- `Dockerfile`: Docker image configuration
- `k8s/`: Kubernetes manifests for deployment

## Running Locally

1. Install dependencies: `pip install -r requirements.txt`
2. Run the app: `python src/app.py`

## Docker

Build and run:

```bash
docker build -t your_username/flask-app:latest .
docker run -p 5000:5000 your_username/flask-app:latest
```

## Kubernetes with Argo CD

Deploy using Argo CD pointing to the `k8s/` directory.
