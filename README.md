 📊 WhatsApp Chat Analysis

Analyze exported WhatsApp chats to uncover activity trends, top senders, emoji usage, word clouds, and media/link stats. Built with Python.

## ✨ Features
- Message stats: total messages, words, media, links
- Top participants & activity trends (daily, monthly, hourly)
- Common words & word cloud
- Emoji analytics
- Media & link sharing patterns

## 🧰 Tech Stack
- Python 3
- Libraries: `pandas`, `matplotlib`, `wordcloud`, `emoji`

## 🚀 Usage
1. Export chat from WhatsApp as `.txt` (without media)
2. Place file in `data/`
3. Run notebook/script to generate insights & charts

```bash
pip install -r requirements.txt
python src/analyze_whatsapp.py --input data/chat.txt --out outputs/
````

## 📂 Structure

```
├─ data/              # chat file
├─ src/               # code files
├─ notebooks/         # analysis notebook
├─ outputs/           # charts & CSV summaries
└─ README.md
```

## 🔒 Privacy

* Runs locally, your chat data is safe.
* Don’t commit raw chats to GitHub.

Link to analyze whatsapp chats -https://whatsapp-chat-analysis-mtgvxaxusesz8jwgbp9ixy.streamlit.app/



