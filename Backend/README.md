# ⚙️ YourDOST SDE Intern Assignment – Backend (Flask API)

### 👨‍💻 Author
**Shubham Mahind**  
B.Tech CSE (AI & ML), VIT Bhopal  
📧 shubham.mahind27@gmail.com  
🔗 [GitHub](https://github.com/SRM27-code) | [LinkedIn](https://www.linkedin.com/in/shubham-mahind/)

---

## 📘 Overview

This project implements a **simple To-Do CRUD REST API** using **Python Flask**.  
All to-do items are stored in a **local JSON file** (`todos.json`), fulfilling the assignment requirement of  
> “Store data either in memory or in a simple local JSON file (no database required).”

The API supports:
- Creating a new to-do  
- Retrieving all to-dos  
- Updating an existing to-do  
- Deleting a to-do  
- Checking server status  

---

## 🏗 Tech Stack
- **Language:** Python 3  
- **Framework:** Flask  
- **Hosting (for testing):** Ngrok (via flask-ngrok in Colab)  
- **Data Storage:** Local JSON file (`/content/todos.json`)

---

## 🚀 How to Run (Google Colab or Local Machine)

### 🧩 In Google Colab
1. Copy the complete `app.py` code into a Colab cell.  
2. Run the cell — Flask and Ngrok will install automatically.  
3. A link will appear such as:

Running on https://xxxx.ngrok.io

Use that URL in Postman or Python `requests` to test your API.

### 💻 Option 2 – Run Locally
```bash
pip install flask
python app.py

Server starts at:

http://127.0.0.1:5000
