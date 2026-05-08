# WhatsApp Chat Analysis & Sentiment Detection 📊💬

A Python-based **WhatsApp Chat Analyzer** that extracts, processes, and visualizes chat statistics from exported WhatsApp chats.  

This project performs:

- 📈 Chat statistics analysis
- 😊 Sentiment analysis using NLP
- 😂 Emoji usage analysis
- ☁️ Word cloud generation
- 🔗 URL counting
- 📊 Interactive visualizations with Plotly

---

# 🚀 Features

- Parse exported WhatsApp chat files
- Detect:
  - Total messages
  - Media messages
  - Emojis used
  - Shared links
- Perform sentiment analysis using NLTK VADER
- Generate emoji statistics
- Create beautiful word clouds
- Interactive emoji bar charts using Plotly
- User-wise chat statistics

---

# 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Plotly**
- **NLTK**
- **WordCloud**
- **Emoji**
- **Regex**

---

# 📂 Project Structure

```bash
WhatsApp-Chat-Analyzer/
│
├── WhatsApp Chat.txt        # Exported WhatsApp chat file
├── chat_analysis.py         # Main Python script
├── requirements.txt         # Required libraries
├── README.md                # Project documentation
└── output/                  # Generated plots & visualizations
```

---

# 📥 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/WhatsApp-Chat-Analyzer.git
cd WhatsApp-Chat-Analyzer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 📦 Required Libraries

You can install all dependencies manually:

```bash
pip install pandas numpy matplotlib plotly nltk wordcloud emoji pillow
```

---

# 📄 Export WhatsApp Chat

1. Open WhatsApp
2. Open any chat
3. Click:
   - **More Options → More → Export Chat**
4. Select:
   - **Without Media**
5. Save the file as:

```bash
WhatsApp Chat.txt
```

Place it inside the project folder.

---

# ▶️ Run the Project

```bash
python chat_analysis.py
```

---

# 📊 Functionalities Explained

## 1️⃣ Chat Parsing

The script reads and extracts:

- Date
- Time
- Author
- Message

from WhatsApp chat logs using **Regular Expressions (Regex)**.

---

## 2️⃣ Sentiment Analysis 😊😠🙂

Using NLTK's VADER sentiment analyzer, the project calculates:

- Positive score
- Negative score
- Neutral score

Example:

```python
sentiments.polarity_scores(message)
```

Final overall sentiment is classified as:

- Positive 😊
- Negative 😠
- Neutral 🙂

---

## 3️⃣ Emoji Analysis 😂

Counts total emojis used in chats.

Example output:

```bash
Total emojis used: 245
```

---

## 4️⃣ URL Detection 🔗

Detects all shared links using regex patterns.

Example:

```python
URLPATTERN = r'(https?://\S+)'
```

---

## 5️⃣ User Statistics 👤

For each user:

- Messages sent
- Average words per message
- Emojis used
- Media shared
- Links shared

---

## 6️⃣ Word Cloud ☁️

Generates word clouds showing frequently used words by each user.

---

## 7️⃣ Emoji Visualization 📈

Interactive Plotly bar chart showing:

- Top emojis used
- Frequency counts

---

# 📷 Sample Outputs

## Word Cloud

```bash
Shows frequently used words visually
```

## Emoji Chart

```bash
Top 15 most used emojis
```

## Sentiment Result

```bash
Positive 😊
```

---

# 🧠 Core Concepts Used

- Natural Language Processing (NLP)
- Sentiment Analysis
- Data Cleaning
- Data Visualization
- Regex Parsing
- Statistical Analysis

---

# 📌 Example Statistics Output

```bash
Chats between User1 and User2

Total Messages:  1200
Number of Media Shared:  85
Number of Emojis Shared:  430
Number of Links Shared:  52
```

---

# ⚠️ Important Notes

- Export chat **without media**
- Ensure UTF-8 encoding
- Replace:

```python
l = ["User1", "User2"]
```

with actual participant names from your chat.

---

# 🔮 Future Improvements

- Streamlit Web App
- Dashboard UI
- Monthly/Weekly analysis
- Most active time detection
- Message heatmaps
- AI-based emotion prediction
- Chat reply time analysis

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by **Satyam Samanta**

- Computer Science Engineering Student
- Passionate about AI, Data Science & Full Stack Development

---

# ⭐ Support

If you liked this project:

- ⭐ Star the repository
- 🍴 Fork the project
- 📢 Share with others

---
