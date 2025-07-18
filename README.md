
# 🐔 HenWell Poultry Management System

HenWell is a **complete poultry management system** built with **PHP, MySQL, Bootstrap, and Python (Flask AI)**.  
It helps farmers manage poultry batches, feed calculation, egg production, supply stores, and AI-based disease detection.

---

## ✨ Features

✅ **Batch Management** – Add, edit, and delete poultry batches (Layer/Broiler).  
✅ **Feed Calculator** – Auto-calculate feed quantity & cost based on batch size & duration.  
✅ **Egg Production Tracker** – Record daily egg production with revenue summary.  
✅ **Nearby Supply Stores** – Filter poultry stores by state & district + Google Maps integration.  
✅ **AI Disease Detection** – Upload chicken images to detect common diseases via a Flask AI model.  
✅ **Clean & Responsive UI** – Built with Bootstrap 5 for mobile & desktop.  

---

## 📂 Project Structure

```
HenWell/
│── assets/               # Background images & icons
│── uploads/              # Uploaded images (ignored in GitHub)
│── batch_management.php  # Manage poultry batches
│── feed.php              # Feed calculator & recent feed logs
│── egg_production.php    # Egg production entry & summary
│── stores.php            # Nearby poultry supply stores + map
│── detection.php         # AI-based disease detection (PHP -> Flask API)
│── db_connection.php     # Database connection file
│── dashboard.php         # Main dashboard
│── python-api/           # Flask AI model for disease detection
│── README.md             # Project documentation (this file)
```

---

## 🚀 Tech Stack

- **Backend:** PHP + MySQL  
- **Frontend:** Bootstrap 5, HTML, CSS, JS  
- **AI Model:** Python (Flask + PyTorch)  
- **Maps:** Google Maps API  

---

## 🔧 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YourUsername/HenWell-Poultry-Management.git
cd HenWell-Poultry-Management
```

### 2️⃣ Import Database
- Create a MySQL database `poultry_db`
- Import `poultry_db.sql`

### 3️⃣ Run PHP Project
- Start **XAMPP**
- Move project to `htdocs`
- Visit `http://localhost/HenWell/dashboard.php`

### 4️⃣ Setup Flask AI Detection
```bash
cd python-api
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # macOS/Linux

pip install -r requirements.txt
python app.py
```

Now AI model runs at `http://127.0.0.1:5000/predict`

---

## 📜 License

**No License (All Rights Reserved)**  
This repository is for **showcasing purposes only**.  
You can view the code but **not allowed to reuse, copy, or distribute without permission**.

---

## 🤝 Credits

- Built by **Ambati Venkata Ratna Sowmya**  
- Uses Google Maps API, Bootstrap 5, and Flask AI model

---

## 📬 Contact

💌 For inquiries or collaboration: **[YourEmail@example.com]**  
📺 [Optional: Add a demo video link here]  

---

⭐ **If you like this project, give it a star on GitHub!**
