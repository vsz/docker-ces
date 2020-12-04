FROM python
LABEL author="Certi-CES"
LABEL description="CES Python container"
COPY src/. /code
WORKDIR /code
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "-u", "hello.py"]
