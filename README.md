# Felicia AI starter

Mobile-first AI companion MVP with burgundy/rose-gold styling, browser-saved chat history, an Express backend, and protected server-side AI API integration.

## Run locally
1. Install Node.js 20 or newer.
2. Run `npm install`.
3. Copy `.env.example` to `.env` and add your provider API key (optional for preview mode).
4. Run `npm run build && npm start`.
5. Open http://localhost:3000.

## Deploy to Render
Create a **Web Service** from this GitHub repository. Runtime: Node. Build command: `npm install && npm run build`. Start command: `npm start`. Add `AI_API_KEY`, `AI_API_URL`, and `AI_MODEL` in Render Environment if you want live AI replies. The server listens on Render's `PORT`.

## MVP limitations
Chat history is stored only in each visitor's browser. No account login, cloud sync, database memory, voice calling, image generation, moderation dashboard, or payment system yet. Live AI requires a provider key and may have provider costs. Never commit `.env` or publish API keys.
