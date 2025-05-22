STUDENT REVIEW ANALYZER - README

========================================
📌 PROJECT SUMMARY
========================================
Student Review Analyzer is a data-driven project that utilizes Natural Language Processing (NLP) to analyze feedback collected from students at institutions like Amity University and Kurukshetra University (KUK). The system processes responses gathered via Google Forms to extract and visualize common themes, sentiments, and frequently used words.

It aims to provide meaningful insights to administration and faculty to improve academic and campus experiences.

========================================
🚀 TECHNOLOGIES USED
========================================
- Python 3.x
- Pandas
- NLTK (Natural Language Toolkit)
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook (or standard Python script)

========================================
▶️ HOW TO RUN THE CODE
========================================
1. Clone the Repository:
   git clone https://github.com/yourusername/student-review-analyzer.git
   cd student-review-analyzer

2. Install Required Packages:
   pip install pandas matplotlib seaborn wordcloud nltk

3. Download NLTK Resources:
   In a Python shell or script, run:
     import nltk
     nltk.download('stopwords')
     nltk.download('punkt')

4. Prepare Your Dataset:
   Place your review data file (e.g., college_reviews.csv) in the project folder.
   Ensure it contains a column named 'review'.

5. Run the Script:
   open the notebook:
   jupyter notebook

========================================
📊 OUTPUT
========================================
- Word cloud image visualizing frequent terms
- Bar chart showing top keywords
- Cleaned and preprocessed text
- CSV with keyword frequency (optional)

========================================
🏫 UNIVERSITIES COVERED
========================================
- Amity University
- Kurukshetra University (KUK)
- Panipat Institute of Engineering and Technology

========================================
📈 FUTURE ENHANCEMENTS
========================================
- Sentiment analysis for positive/negative review classification
- Dashboard with filters for department/semester-wise analysis
- More advanced NLP techniques (e.g., topic modeling)

========================================
👨‍💻 AUTHOR
========================================
Developed by Utkarsh Arora
