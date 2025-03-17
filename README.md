# Baltimore 911 Crime Analysis

## 📌 Overview
This project analyzes 911 crime data in Baltimore to identify crime trends, visualize crime distribution, and provide insights using **Dash (Plotly)**. It includes **interactive visualizations**, such as crime type distribution, temporal patterns, and a heatmap of crime locations.

## 📂 Data
The dataset used in this analysis is stored in the [`data/`](https://github.com/Vrajal99/Baltimore911-Crime-Analysis/tree/main/data) folder and includes:
- **Crime data CSV** files containing details like `CrimeDate`, `Description`, `Latitude`, and `Longitude`.

## 🔧 Installation & Setup
Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Vrajal99/Baltimore911-Crime-Analysis.git
cd Baltimore911-Crime-Analysis
```

### 2️⃣ Create a Virtual Environment (Recommended)
```sh
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Dash App
```sh
python app.py
```
Then, open **http://127.0.0.1:8050/** in your browser to access the dashboard.

## 📊 Features
- **Crime Type Distribution:** Visualizes the frequency of different crime types.
- **Temporal Patterns:** Shows crime trends over time.
- **Map:** Displays a **heatmap** of crime locations using Mapbox.
- **Interactive Filters:** Allows users to filter data by **year, month, and day of the week**.

## 🗂 Project Structure
```
Baltimore911-Crime-Analysis/
│-- data/                # Raw crime data CSVs
│-- app.py               # Dash app (main script)
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation
│-- .gitignore           # Ignores virtual environment & cache files
```

## 📌 Future Enhancements
- 🚀 Add **machine learning** for crime pattern prediction.
- 📈 Improve **dashboard UI** with better filters & themes.
- 🗺️ Integrate **real-time data updates**.

## 🏗 Contributing
1. **Fork the repo** 📌
2. **Create a feature branch** (`git checkout -b feature-name`)
3. **Commit your changes** (`git commit -m "Description"`)
4. **Push to GitHub** (`git push origin feature-name`)
5. **Open a pull request** 🚀

## 📝 License
This project is licensed under the **MIT License**.

---
### 🌟 **Like this project? Give it a ⭐ on [GitHub](https://github.com/Vrajal99/Baltimore911-Crime-Analysis)**! 🚀

