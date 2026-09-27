# Flask AI Chat Prototype

Small Flask application with a chat page and a `POST /chat` endpoint. The API code uses the OpenAI Python client and loads local environment configuration with `python-dotenv`.

## Run locally

Install the packages in `requirements.txt`, provide a valid model-provider API key through your local environment, then run `flask --app api.index run`. Do not commit API keys.

The web page is in `templates/index.html`; the Vercel entry point is `api/index.py`.
