FROM python:3.11.9-slim

ENV PYTHONPATH=/test
COPY req.txt req.txt
RUN pip install -r req.txt

COPY . .

CMD [ "python", "-m", "src.main" ]