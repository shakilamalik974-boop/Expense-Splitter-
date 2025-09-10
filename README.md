# 💸 Smart Expense Splitter

A professional **Expense Splitter Web App** built with **Flask & SQLite**.  
It helps groups of friends, colleagues, or families to **track shared expenses**, **split bills automatically**, and **settle balances** with ease.  
Reports can be exported in **Excel** and **PDF** formats for record-keeping.

---

## ✨ Features
- 👥 **Multiple Groups** → Manage separate trips, events, or parties.  
- ➕ **Add Expenses** → Record who paid, how much, and for whom.  
- 🔄 **Automatic Split** → Each participant’s share is calculated instantly.  
- 📊 **Summary Page** → Shows total expenses and who owes/gets money.  
- 📑 **Export Options** → Download reports in Excel (`.xlsx`) or PDF.  
- 💰 **Currency in Rupees (₹)** for Indian/Pakistani users.  
- 🎨 **Responsive UI** using Bootstrap 5.  

---

## 🛠 Tech Stack
- **Backend:** Python (Flask)  
- **Frontend:** HTML, Jinja2, Bootstrap 5  
- **Database:** SQLite  
- **Reporting:** openpyxl (Excel), reportlab (PDF)  
- **Version Control:** Git & GitHub  

---

## ⚙️ How It Works
1. **Create a Group** → Example: *Trip to Murree*  
2. **Add Expenses** → Select payer, enter amount, participants, and note.  
3. **View Summary** → Instantly see balances for each member.  
4. **Settle Up** → Know exactly who needs to pay whom.  
5. **Export Reports** → Download summary as Excel or PDF.  

---

## 📊 Example
👥 Group: **Trip with Friends**

- Ali paid Rs. 1200 for Dinner (Ali, Sara, John shared)  
- Sara paid Rs. 900 for Lunch (Ali, Sara, John shared)  
- John paid Rs. 600 for Snacks (Ali, Sara, John shared)  

👉 **Final Balances:**
- Ali: +300  
- Sara: -100  
- John: -200  

📥 Report can be downloaded as Excel or PDF.

---

## 🚀 Installation & Usage
```bash
# Clone this repository
git clone https://github.com/your-username/expense-splitter.git
cd expense-splitter

# (Optional) Create virtual environment
python -m venv venv
venv\Scripts\activate       # On Windows
# source venv/bin/activate  # On Mac/Linux

# Install dependencies
pip install flask openpyxl reportlab

# Run the app
python app.py

