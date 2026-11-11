# Praxa RAG

Install dependencies with `pip install -r requirements.txt`. Add your OpenRouter API token to `OPENROUTER_API_KEY` in the local `.env` file, replacing `your_openrouter_api_key_here`. The model reads that file from the project directory. An existing `OPENROUTER_API_KEY` environment variable takes precedence; a key passed to `ChatModel` takes precedence over both.

The local `.env` is ignored by Git. `.env.example` shows the required setting for a fresh checkout.
