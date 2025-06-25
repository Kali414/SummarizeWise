# 🧠 SummarizeWise

**SummarizeWise** is a lightweight and modern web application that provides intelligent text summarization using the **BART Large CNN** model from Hugging Face's Transformers library. It's built with Flask and designed for clarity, simplicity, and speed.

---

## 🚀 Features

- ✂️ Summarize long content into concise highlights
- 🎚 Custom summary length control
- 🧩 Clean, responsive UI with modern glassmorphism styling
- 🧠 Powered by Hugging Face Transformers (BART)
- 🧪 Built using Flask + HTML + TailwindCSS

---

## 💻 Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, TailwindCSS
- **API**: Hugging Face Inference API (`facebook/bart-large-cnn`)

---

## 🛠 Setup Instructions

1. **Clone this repository**

```bash
git clone https://github.com/yourusername/SummarizeWise.git
cd SummarizeWise
```
2. **Create a virtual environment & activate it**
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

```
3. **Install dependencies**
```cssharp
pip install -r requirements.txt
```
## Folder Structure
```csharp
SummarizeWise/
│
├── app.py                  # Flask application
├── templates/
│   ├── home.html           # Landing page
│   └── index.html          # Summarization interface
├── static/                 # CSS, images, and assets
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

```
