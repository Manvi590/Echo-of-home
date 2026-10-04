# Echo of Home — runnable MVP demo

This is a no-build prototype you can run without npm, Python packages, Docker, Postgres or API keys.

## Run
Open `index.html` directly, or run `python -m http.server 8000` in this folder and open `http://localhost:8000`.

## Included
- WhatsApp-inspired family chat
- Text + voice in the same conversation
- Browser microphone recording
- Voice playback using Web Speech API
- Local demo memory retrieval
- Memory source cards
- Memory Vault
- Timeline
- Settings/consent UI
- Responsive mobile layout

Real production work still needs authenticated users, PostgreSQL/pgvector, server-side RAG, object storage, real STT/TTS, and consent enforcement.

Browser voice APIs have varying support; microphone recording uses MediaRecorder and playback uses SpeechSynthesis.
