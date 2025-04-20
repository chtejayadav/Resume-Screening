
# 📄 Resume Screening System

A machine learning-powered tool that automates resume screening by extracting key information and classifying resumes based on job relevance. This solution is designed to support recruiters and HR professionals in quickly identifying top candidates.

## 🚀 Features
- PDF resume parsing and content extraction  
- Job-role classification using ML models  
- Keyword and skill matching  
- Candidate scoring based on relevance  
- Interactive UI built with Streamlit  

## 🛠 Tech Stack
- **Language:** Python 3  
- **Libraries:** scikit-learn, pandas, nltk, pdfminer, Streamlit  
- **Model:** Logistic Regression (easily replaceable)  

## 📁 Project Structure
```
Resume-Screening/
├── app.py            # Streamlit interface
├── resume_parser.py  # Text extraction logic
├── utils.py          # Matching and scoring logic
├── model.pkl         # Pre-trained ML model
├── requirements.txt  # Python dependencies
└── data/             # Sample data and resumes
```

## ⚙️ Getting Started
1. **Clone the Repository**
```
git clone https://github.com/chtejayadav/Resume-Screening.git
cd Resume-Screening
```

2. **(Optional) Create a Virtual Environment**
```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install Dependencies**
```
pip install -r requirements.txt
```

4. **Run the Application**
```
streamlit run app.py
```
Then open your browser and go to `http://localhost:8501`

## 👤 Author
**Ch Teja Yadav**  
[GitHub Profile](https://github.com/chtejayadav)

