# 🤖 Robot Trajectory Prediction using LSTM

## 📌 Overview
This project predicts the future trajectory of a robot using deep learning.

Given the past 10 positions (x, y), the model predicts the next 5 future positions.

The project is 90% Machine Learning and 10% Robotics concept.

---

## 🧠 Method
- Synthetic trajectory generation
- LSTM sequence modeling
- Regression using MSE Loss
- Adam optimizer

---

## 📊 Dataset
Self-generated synthetic robot motion data:
- Random speed
- Random direction
- Slight angular noise

Input Shape: (Batch, 10, 2)  
Output Shape: (Batch, 5, 2)

---

## 🏗 Model
- 2-layer LSTM
- Hidden size: 64
- Fully connected output layer

---

## 📈 Results
Model successfully predicts future robot trajectory.
Evaluation metric: Mean Squared Error (MSE)

---

## 🚀 How to Run
1. Open Google Colab
2. Run all notebook cells
3. Observe trajectory prediction plot

---

## 🔮 Future Improvements
- GRU comparison
- Transformer model
- Longer prediction horizon
- Real-world dataset integration

