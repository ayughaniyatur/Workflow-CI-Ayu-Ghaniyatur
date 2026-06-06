FROM python:3.12-slim

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir \
    mlflow==2.19.0 \
    pandas \
    scikit-learn

CMD ["python", "modelling.py"]