# 📀 Data Sweeper

## 🚀 Overview
Data Sweeper is a **Streamlit-based web app** that allows users to **upload, clean, visualize, and convert CSV/Excel files** efficiently. With built-in data cleaning and visualization features, this tool simplifies handling structured data files.
run app: https://datasweeper-in-python-luufexvmupylfidwguujpn.streamlit.app/
## 🎯 Features
✅ **Upload** multiple CSV/Excel files
✅ **Remove duplicates** and **fill missing values**
✅ **Select specific columns** for data filtering
✅ **Generate visualizations** (Bar Charts)
✅ **Convert** files between **CSV ↔ Excel**
✅ **Download** cleaned & processed files

## 🛠️ Tech Stack & Libraries
- **Streamlit** → For building the interactive web UI
- **Pandas** → For data manipulation & processing
- **OS & BytesIO** → For file handling
- **Matplotlib** (via Streamlit's `bar_chart`) → For visualizations

## 📦 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/SHAJAR5110/DataSweeper-in-python
   ```
2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Mac/Linux
   venv\Scripts\activate  # On Windows
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Streamlit app:**
   ```bash
   streamlit run main.py
or
   python -m streamlit run main.py
   ```

## 📂 Project Structure
```
📂 data-sweeper
├── main.py                # Main Streamlit application

```

## 🤝 Contribution
1. Fork the repository
2. Create a new branch (`feature-new-functionality`)
3. Commit your changes
4. Push to your branch and create a PR

## 📜 License
This project is open-source and available under the **MIT License**.

---
🎉 **Happy Data Cleaning!** 🚀

