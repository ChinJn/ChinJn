# Janice Chin · ChinJn

**Data Risk & Automation Risk Analyst** — I build internal tools that replace manual data processes.

Working on the data side of a forex/CFD brokerage: MT4/MT5 trade data, StarRocks, risk reporting and
data quality. I build local-first tools in Python with local LLMs (Ollama), and ship them as something
a non-technical teammate can click — a bot, a web form, or an installable desktop app.

**Principle:** deterministic code owns the rules and the output. AI summarizes, extracts and drafts.

---

## Projects

**[Data Risk Agent](https://github.com/ChinJn/Data-Team-Agent)** — Lark bot answering the data team's
table-location questions with the exact StarRocks table, a runnable SQL query, and validation steps.
Grounded in a curated data catalog rather than prose RAG. Local Ollama/Qwen; generate-only SQL, no DB
credentials in the bot. `Python · Lark API · Ollama · RAG · StarRocks`

**VSR Automation Tool** — Generates the team's Violation Summary Report from a web form. Replaces a
manual DBeaver → copy-paste → Excel-formula workflow; output is structurally identical to the existing
report. *(internal)* `Python · StarRocks · openpyxl · PyInstaller`

**[Financial News Copilot](https://github.com/ChinJn/News-Bot-Tg)** — Bilingual (EN/繁中) Telegram bot
that collects financial news, summarizes each item with a local Qwen model, and stores it in
PostgreSQL. Fully local inference. `Python · Telegram Bot API · Ollama · PostgreSQL`

**[AI Receipt Tracker](https://github.com/ChinJn/Recipt-Tracker-Bot-TG)** — Telegram bot that turns
receipt photos into structured rows in Google Sheets. Gemini vision extraction, dual-hash duplicate
detection, human-in-the-loop amount correction. `n8n · Gemini · Telegram Bot API · Google Sheets`

**[Trading AI](https://github.com/ChinJn/Combined-Stratergy)** — Research platform for BTCUSD/XAUUSD on
MT5. Data collection, features and risk limits are deterministic and tested; a hard-coded risk engine
has final authority over any model output. Paired with a
[Wyckoff accumulation detector](https://github.com/ChinJn/Wyckoff-Stratergy) in Pine Script.
`Python · MT5 · PostgreSQL · Binance/Bybit APIs`

**[MusicTag](https://github.com/ChinJn/MusicTag-Mac)** — Bulk music-metadata editor for macOS with no
file-count limit. 9 audio formats via TagLib, artwork management, CSV round-trip, full undo/redo.
Ships as a double-click `.app`. `Python · PySide6 · pytaglib`

**[Guitar → Score](https://github.com/ChinJn/music-score)** — Audio in, engraved notation and tablature
out. Basic Pitch → melody extraction → tempo detection → quantize → string/fret assignment by dynamic
programming → MusicXML. `Python · Basic Pitch · librosa · music21 · Verovio`

---

## Stack

**Data** — SQL (StarRocks, PostgreSQL, Oracle) · MT4/MT5 · FXBO · data quality & reconciliation · openpyxl

**Code** — Python · TypeScript/JavaScript · Java · PySide6/Qt · FastAPI · React

**AI** — Ollama (local Qwen) · RAG over curated catalogs · Gemini vision · prompt & eval design

**Automation** — n8n · Telegram / Lark Bot APIs · Playwright · launchd

**Packaging** — PyInstaller · macOS `.app`

---

**BSc Data Analytics**, Sunway University

[LinkedIn](https://www.linkedin.com/in/janice-chin-jie-nee/) · janicechin0420@gmail.com
