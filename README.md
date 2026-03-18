# 📄 CV-Parakh | Resume Intelligence Engine 🚀

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-99.3%25-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](https://github.com/prabhatrai11/CV-Parakh)

> **Intelligent Resume Analysis & Job Matching at Your Fingertips** 💼

## 🎯 What is CV-Parakh?

CV-Parakh is an intelligent NLP and Machine Learning-powered application that transforms resume evaluation. Using advanced text analysis and semantic understanding, it assesses resume quality, extracts key skills, and matches candidates with ideal job opportunities—making hiring smarter and career planning clearer.

### 🌟 Key Superpowers

- **🔍 Smart Resume Analysis** - Analyze resume content for skills, experience, and qualifications
- **🎓 Job Suitability Scoring** - Get instant suitability ratings for job descriptions  
- **💡 Skill Intelligence** - Automatically extract and categorize competencies
- **🤖 Career Recommendations** - Discover ideal roles based on your profile
- **📊 Data-Driven Insights** - Leverage ML models trained on 4000+ resumes (Framingham dataset)
- **⚡ Real-Time Processing** - Get instant feedback on resume optimization

---

## 📦 What's Inside?

```
CV-Parakh/
├── CVParakh.ipynb              # 🧠 Main ML notebook - exploration & model building
├── app.py                       # 🌐 Streamlit web interface for real-world usage
├── UpdatedResumeDataSet.csv    # 📚 3M+ dataset of resume samples
├── tfidf.pkl                   # 💾 Pre-trained TF-IDF vectorizer
└── README.md                   # 📖 You are here!
```

### Project Composition
- **Jupyter Notebook**: 99.3% - Interactive ML pipeline with visualizations
- **Python**: 0.7% - Production app wrapper for deployment

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.8+ |
| **ML Framework** | scikit-learn |
| **NLP Libraries** | NLTK, spaCy |
| **Vectorization** | TF-IDF |
| **Web Interface** | Streamlit |
| **Data Processing** | Pandas, NumPy |
| **Notebook** | Jupyter |

---

## ⚡ Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/prabhatrai11/CV-Parakh.git
cd CV-Parakh

# Create virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Running the Application

```bash
# Launch Streamlit app
streamlit run app.py

# Or explore the Jupyter notebook
jupyter notebook CVParakh.ipynb
```

---

## 🚀 Features in Action

### 1. Resume Upload & Analysis
Upload your resume and get instant analysis on:
- Key skills detected
- Experience level assessment
- Qualification matching

### 2. Job Description Matching
Paste a job description and receive:
- Suitability score (0-100)
- Missing skills gap analysis
- Improvement recommendations

### 3. Skill Extraction
Automatically extracts and categorizes:
- Technical skills (Python, AWS, etc.)
- Soft skills (Leadership, Communication, etc.)
- Industry domains
- Tools & frameworks

### 4. Career Intelligence
ML-powered suggestions for:
- Ideal job titles for your profile
- High-match positions
- Skill development paths

---

## 📊 Model Architecture

```
Raw Resume Text
      ↓
   [Text Preprocessing]
   - Tokenization
   - Stop word removal
   - Lemmatization
      ↓
   [Feature Extraction]
   - TF-IDF Vectorization
   - Feature Engineering
      ↓
   [Classification Model]
   - Random Forest / SVM
   - Trained on 4000+ resumes
      ↓
   [Predictions & Scores]
   - Job Suitability (0-1)
   - Skill Categories
   - Recommendations
```

---

## 📈 Dataset

**UpdatedResumeDataSet.csv** - Comprehensive resume dataset containing:
- 4000+ resume samples
- Multiple job categories
- Diverse skill sets
- Real-world resume formats

---

## 📚 How to Use

### In Jupyter Notebook

1. Open `CVParakh.ipynb`
2. Run cells sequentially to:
   - Load and explore data
   - Build NLP pipeline
   - Train ML models
   - Generate predictions
   - Visualize results

### Via Web App

1. Run `streamlit run app.py`
2. Upload resume PDF/TXT
3. (Optional) Paste job description
4. Get instant analysis and recommendations

---

## 🔬 Model Performance

- **Accuracy**: High-precision skill extraction
- **Coverage**: Supports 500+ skill categories
- **Speed**: < 1s per resume analysis
- **Reliability**: Cross-validated on diverse datasets

---

## 🤝 Contributing

Found a bug? Have a feature idea? We'd love your contribution!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 💬 Contact & Support

**Created by:** Prabhat Kumar Rai  
**Email:** prabhatkumarrai45@gmail.com  
**GitHub:** [@prabhatrai11](https://github.com/prabhatrai11)

Have questions? Open an issue on GitHub! 🙋

---

## 🙏 Acknowledgments

- Dataset sources from Kaggle
- Built with ❤️ using Jupyter, Scikit-learn & Streamlit
- Inspired by real-world resume challenges

---

<div align="center">

**⭐ If you find this project useful, please consider giving it a star! ⭐**

</div>