# Traffic Prediction Using GRU and Reinforcement Learning

Traffic congestion is a growing concern in urban areas due to increasing populations and limited infrastructure. This project leverages deep learning and reinforcement learning techniques to predict traffic flow and adapt signal timing dynamically, aiming to reduce congestion and improve mobility.

## 🚀 Project Overview

* **Objective**: Predict future traffic levels using historical data and optimize traffic signal timing to reduce congestion.
* **Techniques Used**:

  * **Gated Recurrent Unit (GRU)** networks to model and forecast sequential traffic data.
  * **Reinforcement Learning (RL)** for learning adaptive strategies that respond to evolving traffic patterns.

## 🧠 Key Features

* Time-series analysis using deep learning (GRU)
* Stationarity testing and data normalization
* Adaptive signal control via reinforcement learning
* Visualizations for predictions vs actual traffic
* Built and tested entirely in Google Colab

## 🛠️ Tools & Libraries

* Python
* TensorFlow / Keras
* NumPy, Pandas, Matplotlib, Seaborn
* OpenAI Gym (for RL simulation environment)
* Scikit-learn (for preprocessing)

## 📁 Dataset

* Dataset used: `traffic.csv`
* Contains historical traffic volume and signal timing data
* Features include timestamps and various traffic metrics

> *Note: Ensure your own dataset is structured similarly or adjust preprocessing accordingly.*

## 📊 Results

* GRU-based forecasting showed improved accuracy over traditional RNNs.
* RL agent learned to optimize signal timings to reduce peak-time congestion.

## 📓 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/traffic-prediction-GRU-RL.git
   ```
2. Open `Final_Conference_Notebook.ipynb` in Google Colab.
3. Upload or connect the dataset (`traffic.csv`).
4. Run all cells to reproduce results.

## ✅ Future Improvements

* Integrate real-time traffic APIs (e.g., Google Maps)
* Expand to multi-intersection scenarios
* Deploy as a web service with dashboard


