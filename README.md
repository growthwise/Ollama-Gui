# Ollama Chat App 🐐

[![Build and Deploy](https://github.com/ollama-interface/Ollama-Gui/actions/workflows/build-and-deploy.yml/badge.svg?branch=main)](https://github.com/ollama-interface/Ollama-Gui/actions/workflows/build-and-deploy.yml)

Welcome to my Ollama Chat, this is an interface for the Official ollama CLI to make it easier to chat. It includes futures such as:

- Multiple conversations 💬
- Detech which models are available to use 📋
- Auto check if ollama is running ⏰
- Able to change the host where ollama is running at 🖥️
- Perstistance 📀
- Import & Export Chats 🚛
- Light & Dark Theme 🌗

<br />

<img src="./.github/docs/preview-2.png" />

<br />

## How to build on your machine

### Requirements

- [Git](https://git-scm.com/)
- [NodeJS](https://nodejs.org/en) LTS 18
- [pnpm](https://pnpm.io/) 8.8.0+
- [rust](https://www.rust-lang.org/) 1.72.1=

<br />

1.  Clone the repo `git clone git@github.com:ollama-interface/Ollama-Gui.git`
2.  CD into the Directory
3.  `pnpm i` (If you don't have this see here https://pnpm.io/installation and install pnpm first) 
4.  `pnpm build:app:silicon` (:silicon or :intell or :universal) depending on your machine
5.  Go to `/src-tauri/target/release/bundle/dmg/*.dmg` and install the program with the .dmg file.

<br />

You as well you need to install [Ollama](https://ollama.ai) and after you installed it, you can run your local server with this command `OLLAMA_ORIGINS=* OLLAMA_HOST=127.0.0.1:11435 ollama serve`.

<br />
<br />

For any questions, please contact [Twan Luttik (Twitter - X)](https://twitter.com/twanluttik)
