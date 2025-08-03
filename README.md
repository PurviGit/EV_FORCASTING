# EV_FORCASTING 

A data-driven interactive dashboard built using **Streamlit** to analyze and forecast the adoption of Electric Vehicles (EVs) across different counties. Developed as part of the **AICTE Internship Cycle 2** by **Purvi Porwal**.

---

## 📌 Features

- 📍 **County Selection**: Choose a county and view its EV adoption forecast.
- 🔮 **Time-Series Forecasting**: Predict EV adoption for the next 3 years using historical data.
- 📈 **Multi-County Comparison**: Compare up to 5 counties side by side.
- 📊 **Interactive Visualizations**: Includes line charts, bar graphs, and adoption trend indicators.
- 🌙 **Themed UI**: Light-themed dashboard with custom highlight and background colors.
- ✅ **Success Message Insights**: Summarized forecast trends and percentage growth.
- 📂 Local dataset support via CSV upload.

---

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io)
- **Backend/Logic**: Python (Pandas, NumPy, etc.)
- **Forecasting**: Simple lag-based forecasting model (or extend to use ARIMA, Prophet, etc.)
- **Visualization**: Matplotlib, Altair, Streamlit Charts

---

## 🧑‍💻 How to Run the App

### 🔄 1. Clone the Repository

```bash
git clone https://github.com/PurviGit/EV_FORCASTING.git
cd EV_FORCASTING
```
▶️ 2. Install Dependencies
pip install -r requirements.txt

🚀 3. Launch the Streamlit App
streamlit run app.py

Once running, open the displayed localhost or Network URL link in your browser.

📁 Project Structure
EV-FORCASTING/
├── EV_Forcasting.ipynb # Jupyter Notebook for EDA & model experimentation
├── Electric_Vehicle_Population_By_County.csv # Raw dataset
├── preprocessed_ev_data.csv # Cleaned and preprocessed dataset
├── forecasting_ev_model.pkl # Trained forecasting model
├── app.py # Main Streamlit app file
├── ev-car-factory.jpg # Header image for the app
├── requirements.txt # Python dependencies
└── README.md # Project documentation (you're reading this!)

📌 Notes
Customize visuals, background colors, and text formatting using st.markdown() and HTML.

If you encounter issues like IndexError: list index out of range, make sure your dataset has enough historical data points.

✍️ Author
Purvi Porwal
👩‍💻 AICTE Internship Cycle 2 – AIECTE Edunet Shell Internship 

🔗 LinkedIn Profile : www.linkedin.com/in/purvi-porwal-a6554a258

git clone https://github.com/PurviGit/EV_FORCASTING.git

cd ev-adoption-dashboard
