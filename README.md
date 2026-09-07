# Puter AI Chat — Fixed
Single-file build: all CSS and JavaScript are inside index.html.

IMPORTANT: Puter.js requires an HTTP(S) origin, not an Android content:// preview or file:// URL.
Run on a computer with:
python -m http.server 8080
Then open http://localhost:8080

The app uses https://js.puter.com/v2/, puter.ai.chat() for streaming chat, and puter.ai.listModels() so the model dropdown contains models actually exposed by Puter. Default fallback is gpt-5-nano.