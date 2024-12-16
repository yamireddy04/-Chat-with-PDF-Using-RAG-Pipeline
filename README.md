# Langchain RAG Tutorial

Install dependencies.

```python
pip install -r requirements.txt
```

Create the Chroma DB.

```python
python create_database.py
```

Query the Chroma DB.

```python
python query_data.py "why did the peasant decide to camp by the gates of the palace ?"
```

You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.
