


🌿 CarbonCount: A Carbon Emission Tracker

CarbonCount is a Streamlit-based web application that helps users estimate their daily carbon footprint based on electronic device usage, home appliances, and travel choices. It also provides personalized emission tips and downloadable PDF reports.


🚀 Features

 🌍 Tracks emissions from **devices, appliances, and vehicles**
 📍 Auto-detects **user city** and gives **localized tips**
 📊 **Pie chart visualization** of emissions
 📄 Downloadable **PDF report** (auto-generated)
 🌙 **Dark mode** support
 🧠 Smart **eco suggestions** based on usage
 🎮 *(Coming soon)*: **Gamification** with eco-badges!

---

📦 Installation

 1. Clone the repository

```bash
git clone https://github.com/yourusername/carboncount-tracker.git
cd carboncount-tracker
```

2. Create a virtual environment (recommended)

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

🧾 Requirements

Make sure you have [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) installed.

Download the Windows version
Place the `.exe` path correctly in your code like this:

```python
pdfkit.configuration(wkhtmltopdf=r"C:\Program Files\wkhtmltopdf\bin\wkhtmltopdf.exe")
```

---

 ▶️ Run the App

```bash
streamlit run app.py
```

---

 🗂 Project Structure

```
carboncount-tracker/
│
├── app.py                      # Main Streamlit app
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
├── [other .py files]           # Supporting modules (optional)
```

---

 📄 Sample Report Output

 Total CO₂ Emission
 Breakdown by category (device, appliance, vehicle)
 City-based tip
 Emission advice and reduction strategies
 Downloadable as PDF

---

 ✨ Future Enhancements

 🧑‍💻 **Gamification** (badges like "Eco Saver")
 🔒 User login & history tracking
 🌐 Multilingual support
 📈 Monthly trends dashboard

---

 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

 📜 License

[MIT License](LICENSE)

---


