<div align="center">

<!-- Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=2563EB&height=200&section=header&text=Student%20Management%20System&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Modern%20Desktop%20ERP%20%7C%20Python%20%2B%20CustomTkinter%20%2B%20MySQL&descAlignY=58&descAlign=50" width="100%"/>

<!-- Badges Row 1 -->
<p>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/CustomTkinter-5.2+-2563EB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-8.0+-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pillow-10.0+-FFD43B?style=for-the-badge&logo=python&logoColor=black"/>
</p>

<!-- Badges Row 2 -->
<p>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-informational?style=for-the-badge&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge"/>
</p>

<!-- Stars / Forks / Issues -->
<p>
  <img src="https://img.shields.io/github/stars/yourusername/student-management-system?style=social"/>
  &nbsp;
  <img src="https://img.shields.io/github/forks/yourusername/student-management-system?style=social"/>
  &nbsp;
  <img src="https://img.shields.io/github/issues/yourusername/student-management-system?style=social"/>
</p>

<br/>

> 🎓 **A production-ready School ERP Desktop Application** built with Python, CustomTkinter & MySQL.  
> Manage students, generate QR codes, search records — all in a sleek modern UI.

<br/>

[🚀 Quick Start](#-quick-start) • [✨ Features](#-features) • [📸 Screenshots](#-screenshots) • [🗂️ Project Structure](#️-project-structure) • [🛠️ Tech Stack](#️-tech-stack) • [🤝 Contributing](#-contributing)

</div>

---

## 📸 Screenshots

<div align="center">

| 🏠 Main Dashboard | 📋 Student Form | 📱 QR Code Panel |
|:-:|:-:|:-:|
| ![Dashboard](https://via.placeholder.com/380x220/2563EB/ffffff?text=Main+Dashboard) | ![Form](https://via.placeholder.com/380x220/1D4ED8/ffffff?text=Student+Form) | ![QR](https://via.placeholder.com/380x220/16A34A/ffffff?text=QR+Code+Panel) |

| 🔍 Search & Filter | ✏️ Edit Student | 🗑️ Delete Confirm |
|:-:|:-:|:-:|
| ![Search](https://via.placeholder.com/380x220/64748B/ffffff?text=Search+Feature) | ![Edit](https://via.placeholder.com/380x220/D97706/ffffff?text=Edit+Student) | ![Delete](https://via.placeholder.com/380x220/DC2626/ffffff?text=Delete+Dialog) |

</div>

---

## ✨ Features

<div align="center">

```
╔═══════════════════════════════════════════════════════════════════╗
║                    🌟 CORE FEATURES                               ║
╠═══════════════════════════════════════════════════════════════════╣
║  👨‍🎓 Full CRUD         │  ➕ Add  ✏️ Edit  🗑️ Delete  👁️ View      ║
║  🔍 Smart Search       │  Filter by Enrollment, Name, or Class    ║
║  📱 QR Code System     │  Auto-generate + Preview + Download      ║
║  ✅ Form Validation    │  Mobile, Email, Duplicates, Required      ║
║  📊 Live Data Table    │  Sortable, Scrollable, Double-click Edit  ║
║  🔢 Auto Enrollment    │  Sequential STU0001, STU0002 …           ║
║  🎨 Modern Light UI    │  Blue accent, Rounded cards, Clean fonts  ║
║  🏗️  MVC Architecture  │  Separate DB, View, Controller layers     ║
╚═══════════════════════════════════════════════════════════════════╝
```

</div>

### 🎯 Feature Breakdown

<table>
<tr>
<td width="50%">

**📋 Student Management**
- Add new students with 14 data fields
- Edit any record with double-click
- Delete with confirmation dialog
- Auto-generates sequential Enrollment Numbers (`STU0001`)
- Prevents duplicate Enrollment Numbers

</td>
<td width="50%">

**🔍 Search & Filter**
- Live search as you type (no button needed)
- Filter by: All Fields / Enrollment No / Name / Class
- Click any column header to **sort** the table
- Alternating row colors for easy reading

</td>
</tr>
<tr>
<td width="50%">

**📱 QR Code System**
- Auto-generates QR on every new student added
- QR encodes the **Enrollment Number** only
- Preview panel shows QR in real-time
- Download QR as PNG to any location
- Stored in `qrcodes/STU0001.png` format

</td>
<td width="50%">

**✅ Smart Validation**
- All required fields checked before save
- Mobile: exactly 10 digits enforced
- Email: regex format validation
- Date: `YYYY-MM-DD` format check
- Duplicate Enrollment Number detection

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Version | Purpose |
|:---:|:---:|:---|
| <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/> | 3.10+ | Core language |
| <img src="https://img.shields.io/badge/CustomTkinter-2563EB?style=flat&logo=python&logoColor=white"/> | 5.2+ | Modern GUI framework |
| <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/> | 8.0+ | Relational database |
| <img src="https://img.shields.io/badge/mysql--connector-4479A1?style=flat&logo=mysql&logoColor=white"/> | 8.3+ | Python ↔ MySQL bridge |
| <img src="https://img.shields.io/badge/qrcode-222222?style=flat&logo=qrcode&logoColor=white"/> | 7.4+ | QR code generation |
| <img src="https://img.shields.io/badge/Pillow-FFD43B?style=flat&logo=python&logoColor=black"/> | 10.0+ | Image processing |

</div>

---

## 🗂️ Project Structure

```
📦 student_management_system/
│
├── 🐍 app.py                  ← Main application entry point (View + Controller)
├── 🐍 database.py             ← MySQL layer — all CRUD operations (Model)
├── 🐍 validators.py           ← Input validation utilities
├── 🐍 qr_manager.py           ← QR code generation & file management
├── ⚙️  config.py              ← DB credentials & theme color settings
│
├── 📄 requirements.txt        ← Python dependencies
├── 🗄️  setup_database.sql     ← MySQL schema setup script
│
├── 📁 qrcodes/                ← Auto-created — stores QR PNG files
│   ├── STU0001.png
│   ├── STU0002.png
│   └── ...
│
└── 📖 README.md
```

### 🏗️ Architecture — MVC Pattern

```
┌─────────────────────────────────────────────────────────┐
│                     app.py (View + Controller)          │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐  │
│  │  Form Panel  │  │  Table Panel │  │   QR Panel   │  │
│  │  (CTkWidgets)│  │  (Treeview)  │  │  (Preview)   │  │
│  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘  │
└─────────┼────────────────┼────────────────┼────────────┘
          │                │                │
          ▼                ▼                ▼
┌─────────────────┐  ┌──────────────┐  ┌──────────────┐
│  validators.py  │  │  database.py │  │ qr_manager.py│
│  (Validation)   │  │  (Model/DB)  │  │  (QR Logic)  │
└─────────────────┘  └──────┬───────┘  └──────────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │  MySQL Database  │
                    │   student_db    │
                    └─────────────────┘
```

---

## 🗄️ Database Schema

```sql
DATABASE: student_db

TABLE: students
┌──────────────────┬──────────────────┬────────────────────────┐
│ Column           │ Type             │ Notes                  │
├──────────────────┼──────────────────┼────────────────────────┤
│ id               │ INT AUTO_INC PK  │ Internal primary key   │
│ enrollment_no    │ VARCHAR(20)      │ UNIQUE — e.g. STU0001  │
│ student_name     │ VARCHAR(100)     │ Full name              │
│ father_name      │ VARCHAR(100)     │                        │
│ mother_name      │ VARCHAR(100)     │                        │
│ class_name       │ VARCHAR(30)      │ 1–12                   │
│ section          │ VARCHAR(10)      │ A–E                    │
│ dob              │ DATE             │ YYYY-MM-DD             │
│ gender           │ VARCHAR(10)      │ Male/Female/Other      │
│ mobile           │ VARCHAR(15)      │ 10-digit validated     │
│ email            │ VARCHAR(100)     │ Regex validated        │
│ address          │ TEXT             │                        │
│ city             │ VARCHAR(50)      │                        │
│ state            │ VARCHAR(50)      │                        │
│ admission_date   │ DATE             │ YYYY-MM-DD             │
│ created_at       │ TIMESTAMP        │ Auto-set on insert     │
│ updated_at       │ TIMESTAMP        │ Auto-updated on edit   │
└──────────────────┴──────────────────┴────────────────────────┘
```

---

## 🚀 Quick Start

### Prerequisites

Make sure you have the following installed:

- ✅ [Python 3.10+](https://python.org/downloads)
- ✅ [XAMPP](https://apachefriends.org) (or any MySQL 8.x server)
- ✅ pip (comes with Python)

---

### ⚡ Installation — 4 Simple Steps

**Step 1 — Clone the repository**

```bash
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system
```

**Step 2 — Install Python dependencies**

```bash
pip install -r requirements.txt
```

**Step 3 — Setup the MySQL database**

> **Using XAMPP phpMyAdmin (Recommended for beginners)**

1. Open XAMPP → Start **Apache** and **MySQL**
2. Visit `http://localhost/phpmyadmin` in your browser
3. Click **New** → Name it `student_db` → Collation: `utf8mb4_unicode_ci` → **Create**
4. Click **SQL** tab → Paste contents of `setup_database.sql` → Click **Go**

> **Using MySQL command line (cmd.exe)**

```bash
mysql -u root -p < setup_database.sql
```

**Step 4 — Configure your database credentials**

Open `config.py` and update:

```python
DB_CONFIG = {
    "host":     "localhost",
    "port":     3306,
    "user":     "root",
    "password": "",          # XAMPP default = empty string
    "database": "student_db",
}
```

---

### ▶️ Run the Application

```bash
python app.py
```

🎉 The application window will launch at **1200×700** resolution.

---

## 📖 Usage Guide

<details>
<summary><b>➕ Adding a New Student</b></summary>

1. The **Enrollment Number** is auto-filled (e.g. `STU0001`)
2. Fill in all required fields marked with `*`
3. Click **➕ Add** button
4. A QR code is automatically generated and shown in the right panel
5. The table refreshes with the new record

</details>

<details>
<summary><b>✏️ Editing a Student</b></summary>

1. **Click any row** in the data table (or double-click)
2. The form fills with that student's data automatically
3. Make your changes
4. Click **✏️ Update** to save

</details>

<details>
<summary><b>🗑️ Deleting a Student</b></summary>

1. Select a student from the table
2. Click **🗑️ Delete**
3. Confirm in the dialog box
4. The QR code file is also removed from `qrcodes/`

</details>

<details>
<summary><b>🔍 Searching Students</b></summary>

1. Type any keyword in the **Search bar** (top right)
2. Choose search type: `All Fields` / `Enrollment No` / `Name` / `Class`
3. Table filters **live as you type** — no button needed
4. Clear the search box to show all students again

</details>

<details>
<summary><b>📱 QR Code Features</b></summary>

- QR is **auto-generated** when you add a student
- Click **⚡ Generate QR** to regenerate at any time
- QR preview appears in the right panel
- Click **⬇️ Download QR** to save the PNG file anywhere on your PC
- All QR files stored in `qrcodes/` folder as `STU0001.png`

</details>

<details>
<summary><b>📊 Sorting the Table</b></summary>

- Click **any column header** to sort ascending
- Click again to sort **descending**
- Alternating row colors help track rows visually

</details>

---

## ⚙️ Configuration

All settings are in `config.py`:

```python
# Database
DB_CONFIG = {
    "host": "localhost",
    "port": 3306,
    "user": "root",
    "password": "",        # Your MySQL password
    "database": "student_db",
}

# Window
WINDOW_SIZE    = "1200x700"
WINDOW_MIN_SIZE = (1100, 650)

# QR Codes
QR_CODE_FOLDER = "qrcodes"
QR_BOX_SIZE    = 10
QR_BORDER      = 4

# Theme Colors
COLORS = {
    "primary":   "#2563EB",    # Blue accent
    "danger":    "#DC2626",    # Red for delete
    "success":   "#16A34A",    # Green for download
    "warning":   "#D97706",    # Amber for update
    ...
}
```

---

## 🐛 Troubleshooting

<details>
<summary><b>❌ "Access denied for user 'root'@'localhost'"</b></summary>

Your MySQL password in `config.py` is wrong.

- **XAMPP default**: `"password": ""` (empty string)
- **Custom MySQL**: use whatever password you set during install

Test your password:
```bash
# In cmd.exe (not PowerShell):
cd C:\xampp\mysql\bin
mysql.exe -u root -p
# Press Enter when asked for password (for blank password)
```

</details>

<details>
<summary><b>❌ "Cannot connect to MySQL" / "MySQL not running"</b></summary>

- Open **XAMPP Control Panel**
- Click **Start** next to **MySQL**
- Wait for the green "Running" status
- Try running the app again

</details>

<details>
<summary><b>❌ PowerShell redirect error with setup_database.sql</b></summary>

PowerShell doesn't support `<` redirection. Use one of these instead:

```powershell
# Option A — PowerShell
Get-Content setup_database.sql | mysql -u root -p

# Option B — Use cmd.exe instead
mysql -u root -p < setup_database.sql

# Option C — phpMyAdmin (easiest)
# Paste SQL content into phpMyAdmin → SQL tab → Go
```

</details>

<details>
<summary><b>❌ "ModuleNotFoundError: No module named 'customtkinter'"</b></summary>

```bash
pip install -r requirements.txt
```

If that fails, install individually:
```bash
pip install customtkinter mysql-connector-python "qrcode[pil]" Pillow
```

</details>

<details>
<summary><b>❌ App window is too small / cut off</b></summary>

Change `WINDOW_SIZE` in `config.py`:
```python
WINDOW_SIZE = "1400x800"   # Larger window
```

</details>

---

## 🗺️ Roadmap

- [x] Full CRUD operations
- [x] QR code generation & download
- [x] Live search & sort
- [x] Input validation
- [x] XAMPP / phpMyAdmin support
- [ ] 📊 Dashboard with charts (student count by class, gender pie chart)
- [ ] 📄 Export to PDF / Excel
- [ ] 🖨️ Print student ID card with QR
- [ ] 🔐 Login / user authentication
- [ ] 📸 Student photo upload
- [ ] 🌙 Dark mode toggle
- [ ] 📧 Email student details
- [ ] 📱 Multiple modules (Fees, Attendance, Results)

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit your changes
git commit -m "Add: AmazingFeature — short description"

# 4. Push to the branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request
```

Please make sure your code:
- ✅ Follows the existing MVC structure
- ✅ Has comments for new functions
- ✅ Includes proper error handling
- ✅ Works with the existing MySQL schema

---



See [LICENSE](LICENSE) for full text.

---

## 👨‍💻 Author

<div align="center">

**Ved Patel**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/Ved52-ui)

</div>

---


---

<div align="center">

**Made using Python & CustomTkinter**
**if you want it connect me**
<img src="https://capsule-render.vercel.app/api?type=waving&color=2563EB&height=100&section=footer" width="100%"/>

</div>
