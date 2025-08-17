

# 🎭 Sentiment Analysis of Classroom Transcripts

This project analyzes **classroom dialogues** to determine sentiment trends (positive, negative, neutral) over time using **Natural Language Processing (NLP)**.  
It leverages **NLTK’s VADER Sentiment Analyzer** and visualizes results with **Matplotlib**.

---

## 🚀 Features
- Preprocesses transcript text by removing stopwords & punctuation
- Performs sentiment analysis (Positive, Negative, Neutral, Compound)
- Generates a sentiment intensity graph across the dialogue timeline
- Easy to adapt for different types of transcripts (meetings, interviews, etc.)
---


## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: `nltk`, `matplotlib`, `re`  

---

## 📂 Project Structure
```

SentimentAnalysis.ipynb   # Main notebook
transcript.txt            # Sample transcript input file
output.png                # Example sentiment graph

````
---
## Libraries Used

  * `nltk` → for stopwords & VADER sentiment analysis
  * `matplotlib.pyplot` → for visualizing sentiment intensities
  * `re` → for text cleaning
## Pipeline

  1. **Load Transcript** → Reads classroom dialogue from a `.txt` file.
  2. **Text Preprocessing** → Cleans text (removes stopwords, punctuations, etc.).
  3. **Sentiment Analysis** → Uses `SentimentIntensityAnalyzer` (VADER) to calculate Positive, Negative, Neutral, and Compound scores.
  4. **Graph Generation** → Plots sentiment intensities across the dialogue timeline.
  **Output**: A **sentiment intensity graph** showing fluctuations in positivity, negativity, and neutrality of the transcript over time.



---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   cd sentiment-analysis


2. Install dependencies:

   ```bash
   pip install nltk matplotlib
   ```

3. Download required NLTK data:

   ```python
   import nltk
   nltk.download('vader_lexicon')
   nltk.download('stopwords')
   ```

---

## ▶️ Usage

1. Place your transcript file as `transcript.txt`
2. Run the notebook:

   ```bash
   jupyter notebook SentimentAnalysis.ipynb
   ```
3. The program will output a **sentiment graph** like this:

![Sentiment Graph](images/sample_output.png)

---

## 📊 Example Output

* The **blue line** represents positive sentiment intensity
* The **red line** represents negative sentiment intensity
* The **green line** represents neutral sentiment intensity





