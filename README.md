# 你好 👋 Hi, I'm zh-skills

![visitors](https://visitor-badge.laobi.icu/badge?page_id=zh-skills.zh-skills)

I build AI agent skills for Chinese and English users — reusable capabilities that extend AI assistants with practical tools.

> 我为中英文用户开发 AI 技能，让 AI 助手更实用。

---

## 🛠️ Skills Collection

📦 [zh-skills/skills](https://github.com/zh-skills/skills) — AI agent skills you can install with one command

| Skill | What it does |
|-------|-------------|
| `read-webpage` | Fetch plain text from any webpage. Supports English, 简体中文, 繁體中文 |
| `read-webpage-advanced` | Fetch JS-rendered pages using Playwright headless browser |
| `speak-cantonese` | Convert Cantonese text to speech. Online (edge-tts) or local (macOS/Windows) mode. Includes tongue-twister practice files |

### Install
```bash
npx skills add zh-skills/skills@read-webpage
npx skills add zh-skills/skills@read-webpage-advanced
npx skills add zh-skills/skills@speak-cantonese
```

### Use (in your AI chat)
```
use skill read-webpage https://en.wikipedia.org/wiki/Artificial_intelligence
用技能读网页 https://zh.wikipedia.org/wiki/人工智能?variant=zh-hans
用技能讀網頁 https://zh.wikipedia.org/wiki/人工智能?variant=zh-hant
use skill speak-cantonese 各個國家有各個國家嘅國歌
use skill speak-cantonese file skills/speak-cantonese/assets/cantonese-challenge-1.txt
```

---

## 🌐 Languages

Skills and documentation are available in English, Simplified Chinese (简体中文), and Traditional Chinese (繁體中文).
