<h1 align="center">Avaneesh Thakur</h1>
<h3 align="center">Full Stack Developer | AI Engineer | Computer Engineering Student</h3>
<p align="center">
Building scalable web applications, AI-powered products, and modern software solutions.
</p>

---

## About Me

Computer Engineering student with hands-on experience building full-stack web applications and production-grade AI pipelines. Focused on practical systems that solve real problems — clean architecture, defensible technical decisions, and code that can actually scale.

---

## Featured Projects

### ViralLens — RAG Video Engagement Analyzer

A full-stack RAG chatbot that takes a YouTube URL and an Instagram Reel URL, pulls transcripts and metadata for both, and lets you chat with the content. Ask why one video outperformed the other, compare hooks, get engagement rates, or request specific improvements. Responses stream in real time with citations showing exactly which transcript chunk each answer came from.

Runs entirely locally — no OpenAI, no API keys, no monthly bill.

**Stack:** FastAPI, LangGraph, React, ChromaDB, Ollama (llama3.2), sentence-transformers, yt-dlp, Whisper, SSE streaming

**Key decisions:**
- Replaced OpenAI with Ollama to reduce LLM cost from ~Rs.25,000/month to Rs.0 at 1,000 creators/day
- Used direct Ollama HTTP streaming instead of LangGraph astream_events after discovering the latter is unreliable with non-OpenAI models
- Chose ChromaDB over Pinecone for zero-infrastructure local deployment with a clear Qdrant migration path
- Parallel ingestion via asyncio.gather cut total processing time significantly

[View Repository](https://github.com/avaneeshtkur/ViralLens)

---

### Echo Avatar Fusion — AI Video Generation Pipeline

A local-first AI video generation tool that creates talking-head videos from text or audio input. Supports both cloud APIs and local AI services, giving users full control over privacy and cost.

Built around a multi-stage pipeline: speech-to-text via Whisper, text enhancement via GPT, text-to-speech, and lip-sync video generation via Wav2Lip. The architecture is designed to run entirely in-browser or locally — no backend required for most features.

**Stack:** React, TypeScript, Vite, Tailwind CSS, shadcn-ui, Node.js, OpenAI API, Ollama, Whisper, Replicate (Wav2Lip)

**Key features:**
- Local-first architecture — all processing runs locally or in-browser
- Multiple image backends: Ollama (local, private), Stable Diffusion WebUI, or OpenAI DALL-E as fallback
- Bring-your-own-key: use your own OpenAI API key with no backend required
- Mock mode for UI testing without API calls
- Local generation history stored in browser
- Configurable pipeline — swap providers per stage independently

[View Repository](https://github.com/avaneeshtkur/echo-avatar-fusion)

---

### BookMySeat — Movie Ticket Booking Platform

A modern full-stack seat booking platform designed to simplify event and venue reservations through a seamless, user-friendly experience. Users can browse events, select available seats, and complete bookings through an intuitive interface with real-time seat availability.

**Stack:** Next.js, React.js, JavaScript, Tailwind CSS, Node.js, REST APIs, MongoDB, Vercel

**Key challenges solved:**
- Preventing duplicate bookings — implemented backend-side validation to verify seat availability before confirming, with synchronized database updates during reservation requests
- State management across seat selection, authentication, and booking status across multiple pages

[View Repository](https://github.com/avaneeshtkur/BOOKMYSEAT)

---

## Tech Stack

### Languages
<p>
<img src="https://skillicons.dev/icons?i=python,java,cpp,c,javascript,typescript" />
</p>

### Frontend
<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,html,css,bootstrap,tailwind,vite" />
</p>

### Backend
<p>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,django,spring" />
</p>

### Databases and Vector Stores
<p>
<img src="https://skillicons.dev/icons?i=mysql,mongodb" />
</p>

ChromaDB | Qdrant | pgvector

### AI and ML

LangChain | LangGraph | Ollama | Whisper | faster-whisper | sentence-transformers | RAG Pipelines | Vector Embeddings | Local LLMs | SSE Streaming | Wav2Lip | Replicate | OpenAI API | Stable Diffusion

### Tools
<p>
<img src="https://skillicons.dev/icons?i=git,github,docker,figma,vscode,vercel" />
</p>

---



## Contact

- Email: thakuravaneesh620@gmail.com
- Phone: +91 9004285387
- Instagram: [avaneeshtkur](https://instagram.com/avaneeshtkur)
- TopCoder: [Profile](https://www.topcoder.com/members/400001)
- LinkedIn: https://www.linkedin.com/in/avaneesh-thakur-766b35266/
