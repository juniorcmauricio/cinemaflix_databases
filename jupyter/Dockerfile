# Imagem jupyter
FROM jupyter/minimal-notebook:latest

# requirements
COPY requirements.txt .
COPY neo4j_cypher_query.py .

RUN pip install --no-cache-dir -r requirements.txt
