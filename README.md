# 📚 Note Summary and Quiz Generator using Streamlit & Gemini

An AI-powered educational web application that summarizes notes and automatically generates quizzes using Google's Gemini API and Streamlit.

This project helps students, teachers, and self-learners quickly understand large study materials and test their knowledge interactively.

Link: https://note-summary-and-quiz-generator-using-appgemini.streamlit.app/

---

## 🚀 Features

- 📝 Upload study notes
- 🤖 AI-generated concise summaries
- ❓ Automatic quiz generation from notes
- 🎯 Multiple-choice style questions
- ⚡ Fast and interactive Streamlit interface
- 🔥 Powered by Google Gemini AI

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini API**
- **Generative AI**
- **Markdown**

---

## 📂 Project Structure

```bash
Note-Summary-and-Quiz-Generator-using-streamlit_gemini/
│
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── assets/                # Screenshots or static files (optional)
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mohammadsajidhasan/Note-Summary-and-Quiz-Generator-using-streamlit_gemini.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Note-Summary-and-Quiz-Generator-using-streamlit_gemini
```

### 3️⃣ Create a Virtual Environment (Optional but Recommended)

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup Gemini API Key

1. Get your API key from Google AI Studio:
   https://aistudio.google.com/

2. Add your API key in the project:

```python
API_KEY = "YOUR_GEMINI_API_KEY"
```

use environment variables for better security.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The app will open in your browser automatically.

---

## 💡 How It Works

1. User uploads or pastes notes
2. Gemini AI processes the content
3. The app generates:
   - A summarized version of the notes
   - Quiz questions based on the content
4. Users can review and test themselves instantly

---

## 🎯 Use Cases

- Student exam preparation
- Quick revision notes
- Self-assessment quizzes
- AI-assisted learning
- Teacher classroom preparation

---

## 🔮 Future Improvements

- PDF upload support
- Difficulty-level quizzes
- Score tracking
- Export quizzes to PDF
- User authentication
- Multi-language support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

### Md. Sajid Hasan

- GitHub: https://github.com/mohammadsajidhasan

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!
