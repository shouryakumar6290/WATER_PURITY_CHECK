💧 Water Quality Prediction System

A Machine Learning-based project that predicts whether water is safe or unsafe for drinking using various chemical parameters. It also provides confidence score, detects faults, suggests improvements, and visualizes key data.

🚀 Features
✅ Water Quality Prediction (Safe / Unsafe)
📊 Confidence Score
⚠️ Fault Detection
💡 Smart Recommendations
📉 Data Visualization
🚨 Risk Level Indicator
🧪 Input Parameters

The model uses the following water quality parameters:

pH (0–14)
Hardness (0–500)
Total Dissolved Solids (TDS) (0–2000)
Chloramines (0–10)
Sulfate (0–500)
Conductivity (0–1000)
Organic Carbon (0–20)
Trihalomethanes (0–150)
Turbidity (0–10)
🧠 How It Works
User inputs water parameter values
Data is processed using NumPy
Input is passed to trained ML model (clf)
Model predicts:
Water Safety (Safe / Unsafe)
Probability (Confidence Score)
System:
Detects faulty parameters
Provides recommendations
Displays risk level
Generates visualization
📊 Output
🔹 Water Quality: SAFE ✅ / UNSAFE ❌
🔹 Confidence: XX%
🔹 Faults (if detected)
🔹 Recommendations
🔹 Risk Level
📉 Visualization
Bar chart for:
pH
TDS
Turbidity
Includes a safety threshold reference line
🛠️ Tech Stack
Python 🐍
NumPy
Matplotlib
Scikit-learn
