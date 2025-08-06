# Resume_JD_Matcher
# 🧠 Resume vs Job Description Matcher

A simple AI-powered Streamlit app to match a resume with a job description based on semantic similarity using HuggingFace embeddings and FAISS.

---

## 🚀 Features

- Upload your **resume (PDF)**
- Paste the **job description**
- Get a **match percentage score** using embeddings
- Built in **Streamlit**, runs easily on **Google Colab**
- Public link generated via **ngrok**

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Sentence Transformers (`all-MiniLM-L6-v2`)
- FAISS
- PyMuPDF
- Pyngrok

---

## 📦 Installation

### Option 1: Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
Option 2: Run on Google Colab
Upload the .ipynb file to Colab

Run all cells

The last cell will provide a public Streamlit app URL via ngrok

🔑 You'll need an ngrok auth token to expose the app on Colab

🔑 Get ngrok Token
Create an account at https://dashboard.ngrok.com

Copy your auth token

Use it in Colab like:

python
Copy
Edit
!ngrok config add-authtoken YOUR_TOKEN_HERE
📁 Project Structure
bash
Copy
Edit
resume_matcher_project/
├── resume_matcher_project.ipynb     # Main Colab app
└── README.md                        # Project overview
🧪 Example Usage
Upload your resume as a PDF

Paste the job description

Click Match

View the similarity score (out of 100)



📌 Future Improvements
Support for multiple JDs

Resume parsing for key skills

JD parsing via NLP

AI resume suggestions

🧑‍💻 Author
Made by Deepanshu Khurana

📄 License
This project is licensed under the MIT License.
