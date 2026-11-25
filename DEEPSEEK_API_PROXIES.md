# DeepSeek Web Chat → OpenAI-Compatible API Proxies

> Projects that extract `userToken` from browser localStorage and expose a local OpenAI-compatible endpoint for DeepSeek's web chat (chat.deepseek.com). Updated: 2025-11-25

---

## 🎯 Actively Maintained Proxies

| Project | Stars | Last Updated | Key Features |
|---------|-------|--------------|--------------|
| **FreeDeepseekAPI-EN** (atharvotech) | ~1.2k | Recent | English fork of ForgetMeAI; OpenAI/Anthropic compatible; connects to Open WebUI, LiteLLM, Claude Code, any OpenAI SDK; session refresh via `npm run auth` on 401/403/PoW |
| **ds-free-api** (NIyueeE) | ~777 | Recent | OpenAI & Anthropic compatible API proxy for DeepSeek web |
| **Deepseek-API** (sums001) | ~363 | Recent | Reverse-engineers DeepSeek chat → OpenAI-compatible REST API; advertises V4 & R1 models; requests serialized (PoW lock) — sequential throughput |
| **deepseek-free-api** (LLM-Red-Team) | ~2.5k | 2023-2024 | Classic proxy; `/v1/chat/completions`; Bearer `<userToken>` auth; solves SHA-GYT PoW; widely referenced |

---

## 🔧 How They Work

1. **Extract `userToken`** from browser localStorage on `chat.deepseek.com` (DevTools → Console: `localStorage.getItem("userToken")`)
2. **Run local proxy** (Node.js/Python server) with that token
3. **Proxy exposes** `http://localhost:PORT/v1/chat/completions` (OpenAI format)
4. **Connect clients**: Open WebUI, LiteLLM, Cursor, Continue, Claude Code, custom scripts via OpenAI SDK

---

## 📋 Quick Start (FreeDeepseekAPI-EN Example)

```bash
git clone https://github.com/atharvotech/FreeDeepseekAPI-EN
cd FreeDeepseekAPI-EN
npm install
# Get userToken from chat.deepseek.com localStorage
npm run auth -- --token "YOUR_USER_TOKEN"
npm start
# → OpenAI-compatible API at http://localhost:3000/v1
```

**On token expiry (401/403/PoW):**
```bash
npm run auth -- --token "FRESH_USER_TOKEN"
```

---

## ⚠️ Caveats

| Issue | Details |
|-------|---------|
| **Token rotation** | DeepSeek rotates `userToken` on logout, session expiry, or PoW challenge — must re-capture periodically |
| **Rate limits** | Web chat limits apply; some proxies serialize requests (sequential) |
| **Model availability** | Only models visible in your web UI are accessible (V4, R1 if rolled out to your account) |
| **ToS** | Uses unofficial reverse-engineered endpoints; DeepSeek may block/change at any time |
| **Security** | `userToken` = full account access — treat like a password, don't commit to git |

---

## 🔗 Links

- FreeDeepseekAPI-EN: https://github.com/atharvotech/FreeDeepseekAPI-EN
- ds-free-api: https://github.com/NIyueeE/ds-free-api
- Deepseek-API: https://github.com/sums001/Deepseek-API
- deepseek-free-api: https://deepwiki.com/LLM-Red-Team/deepseek-free-api

---

*Created from conversation with AI assistant. Verify project status before production use.*