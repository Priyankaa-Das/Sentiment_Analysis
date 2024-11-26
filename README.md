# 🕵 Sentiment Detection Analyzer

An interactive *sentiment analysis tool* that lets you classify text as *Positive, **Negative**, or **Neutral!** Built with 
🐍 **Python** , 🌐 **Flask**, and 🧠 **TextBlob**, this tool also provides **polarity** and **subjectivity** scores, offering deeper insights into textual sentiment. Whether you're analyzing **customer feedback**, **monitoring** social media trends, or exploring **public sentiments**, this project has you covered.

---
## ✨ Features

- **Sentiment Classification:** Categorizes text as positive, negative, or neutral.

- **Polarity Score**: Measures sentiment intensity on a scale from -1 (negative) to 1 (positive).

- **Subjectivity Score:** Evaluates how subjective or objective the text is (0 for objective to 1 for subjective).

- **Interactive Web Interface:** User-friendly input field to dynamically analyze text in real time.

---

🛠 **Installation and Setup**

Follow these steps to get the project up and running:


Download necessary NLTK corpora for TextBlob:

python -m textblob.download_corpora


**Run the Flask application:**

    python app.py

---
Access the web application: Open your browser and navigate to http://127.0.0.1:5000.

🚀 **Usage**

🔧 **Command-Line Analyzer**

Analyze text directly in your terminal:

python sentiment_detection.py


**Example:**
plaintext
Enter your text: I love this project!
Sentiment: Positive


---
### 🌐 Web Interface
1. Open the application in your browser.
2. Enter your text in the input field.
3. Click **"Submit"** to view sentiment classification, polarity, and subjectivity results.


## 🎯 Example Output
**Input**:  
"I love this project!"

**Output**:  
- **Sentiment**: Positive  
- **Polarity**: 0.8  
- **Subjectivity**: 0.75  

---

## 📋 Requirements
- Python 3.x
- Flask
- TextBlob

---
## 🤝 Contribution

Contributions are welcome!


---

💡 **Pro Tip**: Want to add your own features? Extend the sentiment_detection.py script or enhance the Flask web interface in app.py!

---

Happy analyzing! 🥳
=
