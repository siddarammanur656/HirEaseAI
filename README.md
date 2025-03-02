# HirEase AI 

## 📌 Overview
HirEase AI is a **Smart Resume Analyzer** built using **Streamlit** and **Google Gemini AI**. It allows users to upload their resume and compare it with a job description to analyze how well their profile matches the job role.

## 🚀 Features
- 📂 **Upload Resume (PDF format only)**
- 📝 **Paste Job Description**
- 📋 **Get Resume Details**: AI analyzes strengths, gaps, and improvement areas
- 📊 **Get Resume Match %**: AI calculates match percentage and missing keywords
- ✅ **User-Friendly UI** built with Streamlit

## 🛠️ Tech Stack
- **Streamlit** - Frontend UI
- **Google Gemini AI** - AI-powered resume analysis
- **pdf2image & PIL** - PDF processing
- **dotenv** - Environment variable management

## 📥 Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/siddarammanur656/HirEaseAI.git
   cd HirEase-AI
   ```

2. **Create a Virtual Environment (Optional but Recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set Up API Key**
   - Create a `.env` file in the project root.
   - Add your **Google API Key**:
     ```
     GOOGLE_API_KEY=your_google_api_key_here
     ```

5. **Run the Streamlit App**
   ```sh
   streamlit run app.py
   ```

## 📌 Usage
1. Upload a resume (PDF format only).
2. Paste the job description.
3. Click **"Get Resume Details"** for an AI-driven analysis.
4. Click **"Get Resume Match %"** to calculate match percentage and missing keywords.

## 📷 Screenshots
*To be added*

## 🛠️ Dependencies
- `streamlit`
- `google-generativeai`
- `pdf2image`
- `Pillow`
- `python-dotenv`

## 🤝 Contributing
Feel free to submit pull requests or open issues for feature requests and bug fixes.

## 📜 License
This project is licensed under the MIT License.

---
Made with ❤️ by Siddarama mallanna manur 
