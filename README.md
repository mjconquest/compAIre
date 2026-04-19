# compAIre

A side-by-side AI model comparison tool built as a single self-contained HTML file.

---

## Overview

compAIre sends the same prompt to both Claude (Anthropic) and ChatGPT (OpenAI) simultaneously and displays responses side by side in real time — letting you compare quality, speed, cost, and reasoning depth across models.

## Features

- **Dual streaming API integration** — Anthropic and OpenAI responding simultaneously
- **Model selection** for both providers across multiple available models
- **File attachments** — images and PDFs with proper base64 handling for both APIs
- **Quality and speed voting** to track which model wins over time
- **Per-response cost tracking** with a monthly budget cap
- **Conversation history** with import/export — stored locally in your browser
- **Extended thinking / reasoning visibility** for supported models
- **Side-by-side, stacked, and tabbed layout modes**

## Usage

No install required. Open `compAIre.html` in any modern browser.

Enter your Anthropic API key (from [console.anthropic.com](https://console.anthropic.com)) in the ANT Key field and your OpenAI API key (from [platform.openai.com](https://platform.openai.com)) in the OAI Key field. Both keys are stored only in your browser and sent directly to each respective API — they are never logged or transmitted anywhere else.

## Tech

- React 18 (CDN)
- Anthropic Messages API with streaming
- OpenAI Responses API with streaming
- Marked.js for markdown rendering
- Single file · Zero dependencies · Zero build step
