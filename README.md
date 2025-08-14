# **CoCoder – Real-Time Collaborative Code Editor** 🚀  

CoCoder is a **real-time, web-based collaborative code editor** that allows multiple users to write, edit, and execute code together in the same environment. With **Python** and **C++** execution support, syntax highlighting, and instant updates, CoCoder makes remote coding seamless and engaging.  

---

## ✨ **Features**  

✅ **Real-time Collaboration** – Multiple users can edit the same file simultaneously.  
✅ **Multi-User Rooms** – Create or join unique coding rooms for group sessions.  
✅ **WebSocket Integration** – Instant updates powered by **Flask-SocketIO**.  
✅ **Code Execution Support** – Run Python and C++ code directly in the browser.  
✅ **Syntax Highlighting** – Clean, readable code editing with **CodeMirror**.  
✅ **File Management** – Create, delete, and rename files inside the editor.  
✅ **Docker Support** – Easy deployment with Docker.  

---


## 🛠 **Tech Stack**  

- **Frontend:** HTML, CSS, JavaScript, CodeMirror  
- **Backend:** Python Flask, Flask-SocketIO  
- **Code Execution:** Python, C++  
- **Containerization:** Docker  

---

## 🚀 **Getting Started**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/CoCoder.git
cd CoCoder
````

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
````
### **3️⃣ Run Locally**
```bash
python app.py
````
### **🐳 Run with Docker**
```bash
docker build -t cocoder .
docker run --name cocoder -p 5000:5000 cocoder
````

---
## 🌍 **Usage**  

1. Open the app in your browser.  
2. Create or join a **room**.  
3. Start coding with others in **real-time**.  
4. Execute Python or C++ code and see results instantly. 
