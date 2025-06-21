# 🧮 AI Calculator

An interactive, AI-powered mathematical tool that lets you **draw math problems** on your screen and receive **step-by-step solutions** using **OpenCV** and **Google's Gemini AI**. Designed for a natural and engaging experience, this calculator combines **gesture recognition**, **computer vision**, and **AI reasoning** into one smart application.

---

## 🔍 Overview

The **AI Calculator** transforms traditional math-solving into a futuristic experience by integrating **gesture-based input** with the intelligence of **Google Gemini AI**. Simply draw an equation using your finger — the system recognizes it and returns an accurate, detailed solution.

---

## ✨ Key Features

| Feature                      | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| ✍️ Draw Math Problems        | Use your finger to draw equations on a virtual canvas.                      |
| 🖱️ Move Pointer              | Use two fingers to reposition the drawing pointer.                          |
| 🗑️ Reset Canvas              | Lift your **thumb** to erase and reset the canvas.                          |
| 📤 Send to AI                | Lift your **little finger** to send the drawing for AI interpretation.      |
| 📊 Detailed Step-by-Step Solutions | Get clear, step-by-step solutions powered by **Gemini AI**.          |

### Screenshots

![Demo Screenshot](https://github.com/user-attachments/assets/f53f009a-18e2-4d93-bd14-b9e711e2ebf0)

![image](https://github.com/user-attachments/assets/e8c529bf-0799-440d-9181-63b5ef3fd6eb)
![image](https://github.com/user-attachments/assets/5458b5b1-aa92-4745-b6bc-7cf49280f083)
![image](https://github.com/user-attachments/assets/d9d11cd1-a032-42b5-842f-822b64ef21a9)


---

## 🧰 Tech Stack

- **Python** 🐍  
- **OpenCV** 👁️ – Real-time camera input and gesture recognition  
- **Numpy** ➗ – Matrix operations  
- **Pillow (PIL)** 🖼️ – Image processing  
- **CVZone** 🛠️ – Hand gesture tracking  
- **Google Gemini AI** 🤖 – Solving mathematical expressions  
- **Django** 🌐 – Backend web server and routing  

---

## ⚙️ Installation Guide

### 1. 🔑 Obtain Gemini API Key
- Visit [Google AI Studio](https://aistudio.google.com/) and generate your **Gemini API Key**.

### 2. 📦 Install Dependencies

pip install -r requirements.txt

### 3. 🔐 Configure API Key
Create a .env file in the project root and add:

GEMINI_API_KEY=your_api_key_here
### 4. 🚀 Run the Server

python manage.py runserver
### 5. 🌐 Access the Web App
Visit: http://127.0.0.1:8000

### 📬 Contact
For queries, suggestions, or collaboration:
📧 kseth9852@gmail.com
