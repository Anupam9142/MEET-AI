# Meet-AI

# 📞 AI-Powered Meeting Platform

Build a full-stack platform for **real-time calls with custom AI agents**, **automatic transcripts & summaries**, and a **rich post-call experience** including video playback, transcript search, and AI-powered chat.

---

## 🚀 Features

1. **Real-time Meetings with AI Agents**
   - Use LiveKit for real-time audio/video/WebRTC infrastructure :contentReference[oaicite:1]{index=1}.
   - Integrate OpenAI Realtime Agents API to attach AI assistants during live calls :contentReference[oaicite:2]{index=2}.

2. **Background Transcription & Summarization**
   - Run Whisper/Amazon Transcribe in background jobs after each call.
   - Use GPT (e.g., GPT‑4) to generate concise meeting summaries and minutes.

3. **Post-Call Interface**
   - Record and playback video sessions.
   - View **searchable transcripts** with timestamp-based navigation.
   - Engage with an AI chat assistant that understands the context and answers follow-up questions.

---

## 📦 Tech Stack

| Layer       | Tech / Tools                                     |
|-------------|--------------------------------------------------|
| Frontend    | Next.js, React, Tailwind CSS, LiveKit SDK       |
| Backend     | Node.js, tRPC, Drizzle ORM, PostgreSQL, LiveKit |
| AI Services | OpenAI Agents, Whisper API or Amazon Transcribe |
| Infrastructure | Docker, PostgreSQL, Env vars (.env, docker-compose.yml) |

---

