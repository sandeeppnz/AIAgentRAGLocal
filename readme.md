python -m venv venv
.\venv\Scripts\activate

pip install -r .\requirements.txt

ollama pull llama3.2
ollama pull mxbai-embed-large