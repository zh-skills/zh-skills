# 你好 👋 Hi, I'm zh-skills

![visitors](https://visitor-badge.laobi.icu/badge?page_id=zh-skills.zh-skills)

I build AI agent skills and chat apps for Chinese and English users.

> 我为中英文用户开发 AI 技能和聊天应用。

---

## 🛠️ Skills — [zh-skills/skills](https://github.com/zh-skills/skills)

AI agent skills you can install with one command and use with natural language.

| Skill | What it does |
|-------|-------------|
| `read-webpage` | Fetch plain text from any webpage. Supports English, 简体中文, 繁體中文 |
| `read-dynamic-webpage` | Fetch JS-rendered pages using Playwright headless browser |

### Other Skills

| Repo | What it does |
|------|-------------|
| [pdf-watermark](https://github.com/zh-skills/pdf-watermark) | Add a diagonal text watermark to every page of a PDF file |
| [download-video](https://github.com/zh-skills/download-video) | Download a video from any URL (YouTube, XHS, Bilibili, etc.) using yt-dlp |

### Install
```bash
npx skills add zh-skills/skills@read-webpage
npx skills add zh-skills/skills@read-dynamic-webpage
```

### Use (in your AI chat)
```
use skill read-webpage https://en.wikipedia.org/wiki/Artificial_intelligence
用技能读网页 https://zh.wikipedia.org/wiki/人工智能?variant=zh-hans
用技能讀網頁 https://zh.wikipedia.org/wiki/人工智能?variant=zh-hant
use skill read-dynamic-webpage https://quotes.toscrape.com/js/
用技能讀動態網頁 https://quotes.toscrape.com/js/
```

---

## 💬 Chat Apps

Ready-to-run local AI chat apps with built-in skills. Clone and run — no cloud API needed.

| Repo | Skills | Description |
|------|--------|-------------|
| [chat-with-skills-speak-cantonese](https://github.com/zh-skills/chat-with-skills-speak-cantonese) | speak-cantonese, speak-cantonese-save, speak-cantonese-file | Cantonese TTS — speak sentences and text files aloud |
| [chat-with-skills-speak-english](https://github.com/zh-skills/chat-with-skills-speak-english) | speak-english, speak-english-save, speak-english-file | English TTS — speak sentences and text files aloud |
| [chat-with-skills-transcribe-cantonese](https://github.com/zh-skills/chat-with-skills-transcribe-cantonese) | transcribe-cantonese | Transcribe Cantonese audio files to text using Whisper |

---

## 🌐 Languages

Skills and documentation available in English, 简体中文, and 繁體中文.
