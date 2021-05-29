# Deployment

```bash
export FLASK_APP=main
flask run
```


# Send request

```bash
curl localhost:5000

curl -X POST -d "1" localhost:5000/predict
```


# Docker

```bash
docker build -t bangkit-ml-deployment:latest .

docker run bangkit-ml-deployment:latest
```