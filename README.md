# Resume-Classification-Job-Suggestion-
📄 Resume Ranker (TF-IDF + Machine Learning)

An AI-powered resume screening application that analyzes resumes against job descriptions and predicts candidate-job fit using Natural Language Processing (NLP) and Machine Learning.



---

✨ **Features**

✅ Upload multiple resumes (PDF, DOCX, TXT)

✅ Compare resumes with job descriptions

✅ TF-IDF based resume-job similarity scoring

✅ Machine Learning fit prediction

✅ Skill extraction & matching

✅ Missing skill recommendations

✅ Job role suggestions

✅ Recruiter-friendly ranking system


---



**🔍 How It Works
**

1️⃣ Resume Parsing

The system extracts text from:

PDF files
DOCX files
TXT files


2️⃣ NLP Preprocessing

The extracted text is cleaned by:

Lowercasing
Removing special characters
Tokenization
Stop-word removal

This improves text quality before analysis.



3️⃣ TF-IDF Vectorization

TF-IDF converts text into numerical vectors.

Why TF-IDF?

Captures important keywords
Reduces impact of common words
Lightweight and fast
Works well for resume matching tasks


4️⃣ Feature Engineering

The model uses multiple features:

Feature	Purpose
Cosine Similarity	Measures semantic similarity between resume and JD
Skill Match Count	Counts matching skills
Keyword Overlap	Measures keyword relevance
Resume Length	Captures content richness



5️⃣ Machine Learning Prediction

The engineered features are passed to an XGBoost Classifier.

Why XGBoost?

✔ High accuracy

✔ Handles feature interactions well

✔ Fast training and prediction

✔ Excellent performance on tabular data

✔ Robust against overfitting

**The model predicts:**

🟢 Good Fit
🟡 Potential Fit
🔴 No Fit
🧠 Technologies Used
Programming

Machine Learning & NLP






Backend

Frontend




📊 Model Selection
Model	Reason
TF-IDF	Efficient text vectorization for resume analysis
Cosine Similarity	Measures document similarity effectively
XGBoost	High-performance classification algorithm
NLP Preprocessing	Improves feature quality and prediction accuracy
💻 Run Locally


# Clone repository
git clone https://github.com/yourusername/resume-ranker.git

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py


🎯** Future Improvements**
Resume scoring dashboard
ATS compatibility score
Deep Learning embeddings (BERT/Sentence Transformers)
Resume ranking leaderboard
Job-specific skill gap analysis


📌 **Key Learning Outcomes**
Natural Language Processing (NLP)
TF-IDF Vectorization
Feature Engineering
XGBoost Classification
Flask Web Development
Resume Screening Systems
Machine Learning Deployment
