# DeepSeek Web Chat → OpenAI-Compatible API Proxies

> Projects that extract `userToken` from browser localStorage and expose a local OpenAI-compatible endpoint for DeepSeek's web chat (chat.deepseek.com). Updated: 2025-11-25

---

## 🎯 Actively Maintained Proxies

| Project | Stars | Last Updated | Key Features |
|---------|-------|--------------|--------------|
| **afterburnerr/FreeDeepSeekAPI** ⭐ **BEST FOR HEADLESS** | ~1.2k | Recent | **Docker with Chrome + Xvfb built-in**; `POST /admin/refresh-cookies` works on headless servers; auto cookie refresh via cron; admin endpoints; production logging; Python/DrissionPage |
| **FreeDeepseekAPI-EN** (atharvotech) | ~1.2k | Recent | English fork of ForgetMeAI; OpenAI/Anthropic compatible; connects to Open WebUI, LiteLLM, Claude Code, any OpenAI SDK; session refresh via `npm run auth` on 401/403/PoW |
| **ds-free-api** (NIyueeE) | ~777 | Recent | OpenAI & Anthropic compatible API proxy for DeepSeek web |
| **Deepseek-API** (sums001) | ~363 | Recent | Reverse-engineers DeepSeek chat → OpenAI-compatible REST API; advertises V4 & R1 models; requests serialized (PoW lock) — sequential throughput |
| **deepseek-free-api** (LLM-Red-Team) | ~2.5k | 2023-2024 | Classic proxy; `/v1/chat/completions`; Bearer `<userToken>` auth; solves SHA-GYT PoW; widely referenced |

---

## 🏆 Recommended for Headless Servers: **afterburnerr/FreeDeepSeekAPI**

**Why:** Only fork with **production Docker image** that includes **Chrome + Xvfb + DrissionPage** — enabling fully automated cookie refresh on headless servers via `POST /admin/refresh-cookies` (add to cron).

```bash
# Quick deploy
git clone https://github.com/afterburnerr/FreeDeepSeekAPI
cd FreeDeepSeekAPI
cp .env.example .env
# Edit .env: DEEPSEEK_EMAIL, DEEPSEEK_PASSWORD
docker compose up -d
# → OpenAI-compatible API at http://localhost:8000/v1

# Auto-refresh (cron)
*/30 * * * * curl -X POST http://localhost:8000/admin/refresh-cookies
```

**One-time manual step:** First run may need interactive login if DeepSeek challenges (CAPTCHA/2FA). After that, `refresh-cookies` keeps it alive.

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

- **afterburnerr/FreeDeepSeekAPI (HEADLESS)**: https://github.com/afterburnerr/FreeDeepSeekAPI
- FreeDeepseekAPI-EN: https://github.com/atharvotech/FreeDeepseekAPI-EN
- ds-free-api: https://github.com/NIyueeE/ds-free-api
- Deepseek-API: https://github.com/sums001/Deepseek-API
- deepseek-free-api: https://deepwiki.com/LLM-Red-Team/deepseek-free-api

---

*Created from conversation with AI assistant. Verify project status before production use.*