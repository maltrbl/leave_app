
# Leave Application App (Streamlit)

This is a simple leave application system using Streamlit and CSV-based backend.

## 📦 Features
- Select employee from dropdown
- Auto-fill employee info
- Input leave details (type, dates, reason)
- Upload attachment
- Auto-calculate leave days

## ▶️ How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the app:

```
streamlit run leave_app.py
```

The app will open in your browser at `http://localhost:8501`.

## 📁 Files

- `leave_app.py` – main app file
- `leave_db.csv` – employee data
- `leave_history.csv` – mock leave submissions
