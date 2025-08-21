# logistic-lotka-pinns

A study on using numerical methods and neural networks to simulate and solve differential equations in biological and ecological systems.  

This repository presents a hybrid research project combining **classical mathematical modeling** and **modern deep learning** to solve and analyze differential equations that describe real-world population dynamics. It includes simulations of logistic growth with harvesting, predator-prey cycles using the Lotka-Volterra model, and neural network-based solutions using Physics-Informed Neural Networks (PINNs).

---

## Project Structure

- `diff project.ipynb` – Jupyter notebook with code for all three simulations  
- `diff project.py` – Python script version of the notebook  
- `Differential_Equations.pdf` – Full research paper with explanations and visualizations  
- `README.md` – Project overview and instructions  

---

## Core Topics Covered

### 1. Logistic Growth with Harvesting  
- Models population growth under limited resources  
- Simulates effects of overharvesting on extinction  
- Uses Forward Euler method for numerical solutions  

### 2. Predator-Prey Dynamics (Lotka-Volterra Model)  
- Simulates predator-prey interactions (e.g., rabbits & foxes)  
- Demonstrates oscillatory population cycles  
- Provides phase space and time-series visualizations  

### 3. Solving ODEs using PINNs  
- Solves the equation `dy/dx + 2xy = 0` using a neural network  
- Enforces physical laws in the loss function  
- Trains using TensorFlow with automatic differentiation  

---

## Technologies Used

- Python  
- NumPy  
- Matplotlib  
- TensorFlow (for PINNs)  
- Jupyter Notebook  

---

## Author

**Sri Kalyan Reddy Akiti**  
Data Science and Artificial Intelligence  
