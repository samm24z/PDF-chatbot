# 🧠 AI Project Setup Guide

This guide will help you set up and run the project locally on your machine.

---

## ✅ Prerequisites

- Python 3.8+ installed  
- `pip` package manager  
- A terminal (CMD, PowerShell, or Bash)  
- Your own API keys (for services like OpenAI, Hugging Face, etc.)

---

## ⚙️ Setup Instructions

### 🔹 Step 1: Create a `.env` File

Create a `.env` file in the root directory of the project and add your API keys. Example:

```
OPENAI_API_KEY=your_openai_key  
ANOTHER_API_KEY=your_other_key  
```

---

### 🔹 Step 2: Install Required Packages

Use the following command to install dependencies:

```
pip install -r requirements.txt
```

---

### 🔹 Step 3: Activate Virtual Environment

If not already created, you can create a virtual environment with:

```
python -m venv venv
```

Then activate it:

- **Windows (CMD):**
  ```
  venv\Scripts\activate
  ```

- **Windows (PowerShell):**
  ```
  .\venv\Scripts\Activate.ps1
  ```

- **macOS/Linux:**
  ```
  source venv/bin/activate
  ```

---

### 🔹 Step 4: Run the Application

Navigate to the project folder (if not already there), then run:

```
streamlit run app.py
```

---

### ✅ Step 5: Open in Browser

Once the app launches, it will automatically open in your **default web browser**.  
If not, the terminal will show a local URL which you can copy and paste into your browser.

---

## 🛑 Troubleshooting

- Ensure your `.env` file is properly configured.  
- If `streamlit` is not found, make sure your virtual environment is activated and the package is installed.

---


