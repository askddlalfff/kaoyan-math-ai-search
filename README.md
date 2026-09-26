# Mathematics I Conqueror · kaoyan-math-ai-search (China's National Postgraduate Entrance Exam Math I)

> A purely front-end, single-file, offline-capable learning system for Math I of China's National Postgraduate Entrance Exam: **722 problem-solving models** (model taxonomy refined with an LLM from publicly available lecture materials) + progress tracking + source tracing of past exam questions + gamified conquest map + AI-searchable question bank.
> All data is embedded in the HTML — double-click to use. It can also be paired with a large language model to trace each question on your mock exams back to its source.

## ✨ Feature Overview

### 📗 v14.html — Learning Control Console (Math I Conqueror)
- **📊 Learning Overview**: Predicted exam score (proficient ×100% · not proficient ×60% · don't know ×0%), model coverage, number of study days
- **🗺️ Knowledge Panorama**: A panoramic view of all 722 problem-solving models — light up your journey
- **📚 Knowledge Base**: Browse all models by subject; supports search and sorting by completion status / 2027 predicted probability / chapter
- **✍️ Record Problem-Solving**: Record mastery level for each model (😊 proficient / 🤔 not proficient / 😵 don't know), supports screenshot upload & Ctrl+V paste, and notes
- **📋 Problem-Solving Review**: Filter and review all records
- **🎯 Goals & Levels**: Estimated days to reach your target score; XP level system
- **💾 Backup**: One-click export / import of JSON (localStorage, key `math1_state`)
- **⚔️ Conquest Map Entry**: One-click jump with automatic data sync

### 🗺️ map-v14.html — Conquest Map
- **Gamified map**: 722 "towns" = 722 problem-solving models, Canvas rendering, four-state legend (conquered / in battle / long-unsolved / unexplored)
- **📝 Mock Exam Mode**: Built-in Math I / Math II mock exam framework (user-supplied mock sets supported), view the model each question belongs to, mark mastery, and expand training questions with summaries
- **🏷️ Town Detail Sidebar**: Model quick view, predicted probability, my notes, recommended training
- **🧭 Minimap + town name labels**
- **📥 Data sync**: Export backup in v14 → Import backup in map, or use the Conquest Map entry for automatic sync

### 🤖 How to Use the AI-Searchable Question Bank
Upload `v14.html` along with the mock exam questions you've worked on to any LLM that supports file uploads, and send:
> Starting from a specific question in my mock exam, find the corresponding problem-solving model in v14.html, and then match questions for me in three categories: similar problem structure, similar method, and source tracing to past exam questions.

## 📦 File Description

| File | Description |
|------|-------------|
| `v14.html` | Learning control console (data + records + knowledge base) |
| `map-v14.html` | Conquest map (open in the same directory as v14, or manually import backup) |

## 🚀 Usage
- **Local**: Place both files in the same folder and open `v14.html` in a browser — works offline
- **Online**: Deploy with GitHub Pages and visit directly
- **Data**: The classification of problem-solving methods and question types is derived from publicly available lecture materials and past exam papers (2004–2026). Question texts are user-supplied via import; this repository does not distribute third-party copyrighted content.

## ⚖️ Legal & Compliance
This repository contains only the classification framework (problem-solving models, metadata schema, progress-tracking logic) and does not include any third-party copyrighted question texts. Users are expected to supply their own legally obtained sources (commercial workbooks, mock exam sets, etc.) via the built-in JSON import. Past exam questions are stored as factual metadata only (year, exam type, question number, topic tag); analytical commentary is independently written. For any copyright concerns, please open an issue or contact the maintainer.

## 📄 License
MIT License, for study and communication purposes only.
