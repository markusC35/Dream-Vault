[README.md](https://github.com/user-attachments/files/31647154/README.md)
# Dream Vault — Simple prototype

This is a dependency-free HTML/CSS/JavaScript version of the Dream Vault flow. It uses browser speech recognition for live transcription when supported, with a sample fallback, and browser localStorage. `server.js` also includes an optional `/api/generate-image` endpoint for Gemini image generation when `GEMINI_API_KEY` is configured.

```bash
node server.js
```

Open http://localhost:8080.
