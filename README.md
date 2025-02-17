
# 📊 Queer Slur Analysis on Reddit  

## 📄 Project Overview  
This project investigates the usage and context of **queer slurs** across three different subreddits. Using **web scraping (Reddit API & PRAW), NLP techniques, and collocational analysis**, this study explores how slurs are used in different online spaces, focusing on **performativity, reclamation, and linguistic shifts**.

## 🔍 Research Focus  
- **Which queer slurs appear most frequently in these communities?**  
- **Are these terms used as reclaimed language or in a derogatory manner?**  
- **How do collocates (words surrounding these slurs) impact meaning?**  

## 📂 Data Collection  
- **Source:** Data scraped from Reddit (3 subreddits).  
- **Tools Used:**  
  - `PRAW` for Reddit API access  
  - `BeautifulSoup` for HTML parsing  
  - `NLTK / spaCy` for NLP processing  
- **Corpus:** Collected comments containing the terms: *queer, faggot, dyke, homo*.

## 🛠 Methods & Analysis  
- **Collocational analysis** (Word Window ±3) to examine linguistic patterns.  
- **Sentiment analysis** to assess how slurs are used in context.  
- **Frequency distributions** of slurs and common collocates.

## 📊 Results (Coming Soon)  
- Initial findings suggest that queer slurs used in designated queer spaces such as r/Queer or r/LGBT are used in a more positive or neutral way. In spaces such as r/conservative, queer slurs are used in more inflammatory and hateful contexts. 
- Detailed analysis and visualization to be added.

## 🚀 How to Run This Project  
1. Clone the repository:
   ```bash
   git clone https://github.com/malorieiovino/reddit-slur-analysis.git
