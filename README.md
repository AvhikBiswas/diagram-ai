# 🎬 ManimMCP - AI-Powered 2D Animation Video Generator

ManimMCP is a SaaS platform that lets you generate, edit, and export 2D animated videos using **natural language prompts** powered by **GPT-4** and rendered using the **Manim engine**.

> Think: "ChatGPT meets After Effects for diagrams and system architecture videos."

---

## ✨ Features

- 🧠 **AI-Powered Prompting**  
  Describe your scene (e.g. “Create a server-client architecture where the server is a large blue box”) and get a Manim-rendered animation.

- 🎞️ **Scene-by-Scene Editing**  
  Edit individual scenes by prompt (e.g. “Make the server box red” or “Increase duration of this animation”).

- 🧰 **Visual Scene Manager**  
  Reorder, modify, and regenerate specific scenes — no full re-renders needed.

- 📦 **Video Export**  
  Download `.mp4`, `.gif`, or even PPT-ready exports. Free tier includes watermarked renders.

- 👥 **Collaboration Ready** *(coming soon)*  
  Share, comment, and edit animations with your team or clients.

---

## 🧪 Use Cases

- Architecture / System design explainer videos  
- Educational content (math, algorithms, computer science)  
- SaaS onboarding animations  
- Animated pitch decks or product walkthroughs  
- Technical YouTube videos with clean visuals

---

## 🚀 Tech Stack

| Layer        | Tech                           |
|--------------|--------------------------------|
| Frontend     | React, Tailwind CSS, ShadCN UI |
| Backend      | FastAPI / Node.js (Express)    |
| Rendering    | Python + ManimCE (Dockerized)  |
| AI           | OpenAI GPT-4 API               |
| Auth         | NextAuth / Firebase Auth       |
| Storage      | AWS S3 for videos              |
| Database     | PostgreSQL / Supabase          |
| Deployment   | Vercel (frontend), Render/Railway/Fly.io (backend)

---

## 🧠 How It Works

1. 🗣️ **User enters prompt**  
   _e.g., “Show a flow from client to server and then to database.”_

2. 🤖 **AI converts prompt → Manim Python script**  
   The backend uses GPT-4 to generate valid Manim code.

3. 🐍 **Manim renders the video in Docker**  
   The backend runs Manim CLI to produce a scene as `.mp4`.

4. 📥 **User downloads or edits**  
   Scenes can be edited by re-prompting individual parts.

---

## 📅 Roadmap

- [x] Prompt to Video MVP
- [ ] Scene Memory + Named Objects
- [ ] Drag-and-Drop Scene Manager
- [ ] Team Collaboration
- [ ] Voiceover Sync
- [ ] Commercial Tier & Billing

---

## 📄 License

This project is currently under development and not licensed for commercial use yet.

---

## 🙌 Contributors

Built with ❤️ by [Your Name], AI enthusiast & full-stack developer.

Want to contribute? PRs welcome!

