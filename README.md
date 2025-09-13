# India Data Project

[![Streamlit App](https://img.shields.io/badge/Streamlit-Live_App-red?logo=streamlit)](https://egz4tgciuhbgbgydxsoorm.streamlit.app/)

☝️ **Click the above badge to view the live dashboard**

An **interactive data visualization dashboard** for exploring state-wise data across India.  
Built using **Streamlit** and **Plotly**, this project allows users to filter by state, choose parameters, and visualize insights on an interactive map and charts.  

---

## 🚀 Features
- 📊 Interactive dashboards with charts and maps  
- 🗺️ State-wise data visualization using **Plotly Express scatter_mapbox**  
- 🎛️ Sidebar filters for selecting **state** and **data parameters**  
- 📑 CSV-based dataset (`india.csv`) that powers the visualizations  
- 🌐 Clean, wide-layout design with **Streamlit**  

---

## 📂 Project Structure
```
india-data-project/
│
├── india.csv          # Dataset file containing state-wise data
├── app.py             # Main Streamlit app
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ChiragDhongadi/india-data-project.git
   cd india-data-project
   ```

2. **Create virtual environment (optional but recommended)**
   ```bash
   python -m venv .venv
   source .venv/bin/activate     # Mac/Linux
   .venv\Scripts\activate        # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Streamlit** – for interactive UI
* **Plotly Express** – for charts & maps
* **Pandas / NumPy** – for data handling
