# 🎖️ ALPHA GYN - Strategic Military Reading & Gemini Combat AI Dossier

**Alpha Gyn** is a full-stack tactical defense library and intelligence reading platform. Built with high-contrast military styling (Navy Blue, Crisp White, Tactical Gold/Yellow, and a patriotic Tricolor Ribbon: Orange → White → Green) and integrated with Google's Gemini AI.

---

## 🌟 Key Features

### 1. 🤖 Backend Gemini AI Token Management
- **Instant Admin Integration**: Admin can easily add, update, and test their Google Gemini API Token directly from the **Admin Command Center**.
- **Live Connection Tester**: Ping test button checks authentication and returns latency (ms) and status.
- **Model Selector**: Switch seamlessly between `gemini-1.5-flash`, `gemini-1.5-pro`, and `gemini-2.0-flash`.
- **Reader AI Assistant**:
  - 🌐 **Multilingual Translation**: Translates complex tactical sections into Hindi, Punjabi, Bengali, Tamil, Telugu, Spanish, French, etc.
  - 💡 **Jargon Simplifier**: Explains tactical military terminology into plain recruit terms.
  - 💬 **Contextual Q&A**: Readers can ask any query about the current chapter, strictly grounded in the reading excerpt.
  - 📋 **Executive Mission Briefing**: Generates bulleted summaries of key lessons.

### 2. 📂 Hierarchical Book & Folder Content System
- **Book (with Pic)**: Admin can create books with title, author, category, description, and upload or link book covers.
- **Subfolder Architecture**: Inside each book, create named folders (e.g. `Folder 1: Strategic Estimation`, `Folder 2: Mountain Warfare`) and upload structured reading content.
- Full CRUD operations to edit, update, or remove books and folders.

### 3. 📖 Tactical Reader View
- **Full Screen Toggle**: Enter distraction-free immersive full-screen reading mode.
- **4 Military Themes**:
  - *Night Recon* (OLED Dark & Tactical Navy)
  - *Light Infantry* (Crisp White & Navy)
  - *Field Sepia* (Tactical Parchment Paper)
  - *Army Camo* (Olive Drab & Gold)
- **Zoom In / Zoom Out**: Adjust font size dynamically from 14px to 28px.
- **Font Styles**: Toggle between Modern Sans, Tactical Serif, and Terminal Monospace.
- **Floating AI Combat Support**: One-click drawer to get instant AI help on the text.

### 4. 🪖 Email Sign-In & Reading Performance Dashboard
- **Soldier Email Identification**: Sign in with email to save reading history.
- **Reading Stats**:
  - How many books read (`X / Y Books Mastered`)
  - Folders / Chapters read count
  - Minutes spent studying
  - Reading streak
- **Military Rank Progression**:
  - 🔰 **Cadet Recruit**
  - 🎗️ **Lieutenant Officer**
  - 🎖️ **Captain Field Operative**
  - ⭐ **Major Strategist**
  - 🦅 **Colonel Commander**
- **Which Books are Read**:
  - "Completed Missions" archive (books where all chapters have been mastered)
  - "Active Operations" shelf with percentage progress bars

---

## 🚀 How to Run the Project

```bash
# 1. Start the Express Backend Server (Port 5000)
npm run dev:server

# 2. In another terminal, start the Vite Frontend (Port 5173)
npm run dev:client

# Or run both simultaneously:
npm run dev
```

Visit `http://localhost:5173` in your browser.
