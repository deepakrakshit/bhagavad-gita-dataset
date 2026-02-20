# 📜 Bhagavad Gita – Complete Multilingual Dataset

A clean, structured, machine‑readable dataset of the **Śrīmad Bhagavad Gītā**, containing all **18 chapters** and **700 verses** in multiple languages. This repository focuses purely on the **data**, independent of any app or framework, making it easy to reuse across platforms.

---

## ✨ What’s Included

* ✅ **18 chapters / 700 verses**
* ✅ **Sanskrit** (Devanagari + IAST transliteration)
* ✅ **Hindi** translation and detailed explanation
* ✅ **English** translation and detailed explanation
* ✅ Consistent JSON structure
* ✅ UTF‑8 encoded (safe for Devanagari)

---

## 📂 Folder Structure

```
datasets/
├── chapter_01.json
├── chapter_02.json
├── ...
└── chapter_18.json
```

Each file represents **one complete chapter**, including metadata, verses, and explanations.

---

## 🧾 Verse Format (Example)

```json
{
  "chapter": 6,
  "verse_number": 47,
  "global_verse_id": 280,
  "speaker": "Śrī Bhagavān",
  "sanskrit": {
    "devanagari": "...",
    "iast": "..."
  },
  "hindi": {
    "translation": "...",
    "explanation": "..."
  },
  "english": {
    "translation": "...",
    "explanation": "..."
  }
}
```

---

## 🎯 Intended Use

* 📱 Mobile & web applications
* 🤖 AI / LLM training and grounding
* 🔍 Search & NLP pipelines
* 📚 Education and research

This dataset is **offline‑friendly**, framework‑agnostic, and designed for long‑term reuse.

---

## 📜 License

This dataset is shared for **educational and research purposes**. If you use or adapt it, please provide appropriate attribution.

---

## 🙏 Credits

Compiled and structured with care by **Deepak**.
Inspired by the timeless wisdom of the Bhagavad Gītā.
