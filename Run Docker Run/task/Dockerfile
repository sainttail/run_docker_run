# Write the codes below!
FROM python:3.11-slim

LABEL author=test

ADD hyper-app /hyper-app

RUN pip install -r ./hyper-app/requirements.txt

EXPOSE 8000

ENTRYPOINT [ "python", "./hyper-app/main.py" ]