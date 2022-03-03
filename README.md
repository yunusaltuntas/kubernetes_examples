# kubernetes_examples

## run flusk app in yoour local for testing

pip install -r requirements.txt
python main.py

## crate an image and test it

docker build -f Dockerfile -t hello-python:latest .

docker run -p 8080:8080 hello-python:latest


