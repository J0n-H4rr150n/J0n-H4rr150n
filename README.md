# 👋 Hi, I'm Jon Harrison (@J0n-H4rr150n)

## Current Project - x0v3rt

```
                                _                                          s
                 .n~~%x.       u            .x~~"*Weu.                    :8
   uL   ..     x88X   888.    88Nu.   u.   d8Nu.  9888c     .u    .      .88
 .@88b  @88R  X888X   8888L  '88888.o888c  88888  98888   .d88B :@8c    :888ooo
'"Y888k/"*P  X8888X   88888   ^8888  8888  "***"  9888%  ="8888f8888r -*8888888
   Y888L     88888X   88888X   8888  8888       ..@8*"     4888>'88"    8888
    8888     88888X   88888X   8888  8888    ````"8Weu     4888> '      8888
    `888N    88888X   88888f   8888  8888   ..    ?8888L   4888>        8888
 .u./"888&   48888X   88888   .8888b.888P :@88N   '8888N  .d888L .+    .8888Lu=
d888" Y888*"  ?888X   8888"    ^Y8888*""  *8888~  '8888F  ^"8888*"     ^%888*
` "Y   Y"      "88X   88*`       `Y"      '*8"`   9888%      "Y"         'Y"
                 ^"==="`                    `~===*%"`

```  

# Overview of x0v3rt

## What is x0v3rt?

**x0v3rt** is a cross-platform **Security Operations Workbench** built specifically for bug bounty hunters, penetration testers, and security researchers. It combines note-taking, terminal access, AI assistance, and automation into a single, powerful Electron application that runs natively on Windows, macOS, and Linux.

Think of it as **Obsidian meets VS Code meets a Security OS** — purpose-built for offensive security workflows.

---

## ✨ Key Features

### 📝 Live Markdown Editor with CodeMirror 6
- **Obsidian-style live preview** — Write markdown and see it rendered inline as you type
- **Multi-language syntax highlighting** — CSS, HTML, JavaScript, JSON, Markdown, Python, SQL, XML
- **Auto-save** — Never lose your findings mid-engagement
- **Image support** — Paste clipboard images directly into notes, auto-saved to workspace assets
- **Search & navigation** — Fuzzy file search (Ctrl+P), full-text search across all notes
- **File tree explorer** — Organize notes into folders, rename/move files, hidden files toggle

### 🤖 AI-Powered Assistant
- **Google Vertex AI & Gemini integration** — Chat with advanced AI models directly in the sidebar
- **Context-aware assistance** — AI has access to your notes, providing relevant pentesting advice
- **Multi-model support** — Switch between different AI models (configured via settings)
- **Chat history** — Persistent session management with search across conversations
- **Configurable parameters** — Adjust temperature, top-p, context window, and max output tokens

### 💻 Integrated Terminal (xterm.js + node-pty)
- **Full PTY terminal** — Native shell experience (bash, PowerShell, zsh) inside the app
- **Split panes** — Work with multiple terminals side-by-side
- **Terminal tabs** — Manage multiple shell sessions
- **Resize & maximize** — Flexible terminal panel with drag-to-resize

### 🗂️ Intelligent File Management
- **Workspace-based organization** — Each engagement/project gets its own isolated workspace
- **Front matter metadata** — Track creation/modification timestamps, tags, and custom fields
- **Version control** — Undo save to revert to previous file versions
- **Import files** — Drag external files into your workspace
- **Binary file support** — View images, open PDFs, handle non-text files

### 🧩 Extensible Architecture
- **Extension system** — Browse and install community extensions (planned feature)
- **Modular design** — Clean separation between UI, backend, and AI providers
- **Settings manager** — Centralized configuration with persistent storage
- **Search indexer** — Fast full-text search powered by SQLite FTS5

### 🎨 Modern UI/UX
- **VS Code-inspired interface** — Familiar layout for developers
- **Dark theme** — Easy on the eyes during long bug hunting sessions
- **Resizable panels** — Customize your workspace layout
- **Activity bar** — Quick access to Explorer, Extensions, and AI panels
- **Command center** — Quick search bar in the toolbar

---

## 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| **Framework** | Electron 40 |
| **UI Renderer** | Vite + vanilla JavaScript |
| **Editor** | CodeMirror 6 |
| **Terminal** | xterm.js + node-pty |
| **AI Providers** | Google Vertex AI, Gemini AI |
| **Database** | better-sqlite3 (for search indexing) |
| **Markdown** | markdown-it, marked, DOMPurify |
| **Build System** | electron-builder (cross-platform builds) |

---

## 🎯 Target Use Cases

### Bug Bounty Hunting
- Take notes during reconnaissance
- Store PoC scripts and payloads
- Chat with AI to brainstorm exploitation strategies
- Run tools directly in integrated terminal
- Organize findings by program/target

### Penetration Testing
- Document engagements with markdown reports
- Track vulnerabilities with metadata tags
- Run nmap, burp, ffuf without leaving the app
- Generate final reports from markdown notes

### CTF Competitions
- Quick note-taking during challenges
- AI assistance for reversing/crypto/web challenges
- Terminal access for tool execution
- Organize writeups post-competition

### Security Research
- Document research findings
- Store code snippets and PoCs
- Collaborate with AI on analysis
- Maintain a knowledge base

---

## 🚀 Current Status

**Version:** 0.1.0 (Alpha)  
**Platform Support:** Windows, macOS (Intel/Apple Silicon), Linux (AppImage, Deb)

### What's Working Now
- ✅ Live markdown editor with syntax highlighting
- ✅ Integrated terminal with split panes
- ✅ AI chat with Google Vertex/Gemini
- ✅ File management with workspaces
- ✅ Full-text search across notes
- ✅ Clipboard image pasting
- ✅ Auto-save functionality
- ✅ Cross-platform builds via GitHub Actions

### What's Coming Next
- 🔜 Browser automation (Playwright integration for screenshots/PoC)
- 🔜 Extension features
- 🔜 Customizable AI system prompts for different security testing scenarios
- 🔜 Integration with common security tools (Burp Suite, nmap, etc.)

---

## 💡 Why x0v3rt?

**The problem:** Security professionals juggle multiple tools — Obsidian for notes, VS Code for scripts, iTerm for terminal, ChatGPT for AI — constantly switching context and losing flow.

**The solution:** x0v3rt unifies these workflows into one purpose-built application, letting you focus on finding vulnerabilities instead of managing tools.

**The vision:** Build the ultimate security researcher's workbench — where notes, AI, automation, and execution live in harmony.

---

## 🤝 Support Development

x0v3rt is built by a solo developer passionate about making security research more efficient and enjoyable.

**Your sponsorship helps:**
- 🔬 Dedicate more time to feature development
- 🐛 Fix bugs and improve stability
- 📚 Create tutorials and documentation
- 🌐 Build a community around the project
- ☁️ Maintain cloud infrastructure for future features

Every contribution, no matter how small, keeps this project moving forward. Thank you for believing in this vision! 🙏

---

## 📜 License & Disclaimer

**License:** GPL-3.0
**Use:** Authorized security testing, research, and educational purposes only

> [!CAUTION]
> This software is intended for lawful security testing on systems you own or have explicit written authorization to test. Unauthorized access is prohibited and illegal.

---

## 🔗 Links

- **GitHub:** [github.com/J0n-H4rr150n/x0v3rt](https://github.com/J0n-H4rr150n/x0v3rt)
- **Issues:** [Report bugs or request features](https://github.com/J0n-H4rr150n/x0v3rt/issues)
- **Releases:** [Download latest builds](https://github.com/J0n-H4rr150n/x0v3rt/releases)

---

**Built with 💚 for the security community**

## 💰 Support My Work
- 💖 [GitHub Sponsors](https://github.com/sponsors/J0n-H4rr150n)
- ☕ [Buy Me a Coffee](https://buymeacoffee.com/j0nh4rr150n)

---

<!---
J0n-H4rr150n/J0n-H4rr150n is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
