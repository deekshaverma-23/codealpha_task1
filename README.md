# 🌍 Language Translation Tool

A simple Language Translation Tool built using **Python**, **Streamlit**, and **Google Translate API (via Deep Translator)**. This application allows users to enter text, select source and target languages, and instantly translate text through an easy-to-use web interface.

---

## 📌 Features

* User-friendly interface built with Streamlit
* Supports multiple languages
* Select source and target languages
* Real-time text translation
* Error handling for invalid inputs and API issues
* Fast and lightweight application

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Deep Translator
* Google Translate API

---

## 📂 Project Structure

```text
language_translation_tool/
│
├── venv/
├── app.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd language_translation_tool
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit deep-translator
```

---

## ▶️ Running the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

The application will automatically open in your default browser.

---

## 📖 How It Works

1. Enter the text you want to translate.
2. Select the source language.
3. Select the target language.
4. Click the **Translate** button.
5. The application sends the text to the translation API.
6. The translated text is displayed on the screen.

---

## 🌐 Supported Languages

* English
* Hindi
* French
* German
* Spanish
* Japanese
* Chinese
* Russian
* Arabic
* Korean

Additional languages can be added easily by updating the language dictionary in the source code.

---

## 📸 Sample Workflow

**Input**

```text
Hello, how are you?
```

**Source Language**

```text
English
```

**Target Language**

```text
Hindi
```

**Output**

```text
नमस्ते, आप कैसे हैं?
```

---

## 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

* API Integration
* Frontend Development with Streamlit
* User Input Handling
* Error Handling
* Working with Third-Party Libraries
* Real-Time Data Processing

---

## 🔮 Future Enhancements

* Copy translated text feature
* Text-to-Speech functionality
* Translation history
* Automatic language detection
* Dark mode support

---

## 👨‍💻 Author

Developed as part of an AI Internship Task to demonstrate practical implementation of language translation using API integration and Python-based web development.
