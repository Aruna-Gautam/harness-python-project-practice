touch pythondockerfile
cat > pythondockerfile <<- EOM
FROM python:3.10.6-alpine
WORKDIR /python-pipeline-samples
ADD . /python-pipeline-samples
RUN pip install -r requirements.txt
CMD ["python" , "app.py"]
EOM
cat pythondockerfile
