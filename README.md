Building Heating Load Estimation using Neural Networks
A feedforward neural network built with PyTorch to predict the heating load of residential buildings using the UCI Energy Efficiency Dataset. The model takes 8 building physical parameters as input and predicts the heating load in kWh/m².
Dataset: UCI Energy Efficiency Dataset — 768 samples, 8 features (compactness, surface area, wall area, roof area, height, orientation, glazing area, glazing distribution).
Model: Fully connected network — 8 → 64 → 128 → 64 → 32 → 1 with ReLU activations and Adam optimizer.
Results:
MetricValueMAE0.4544 kWh/m²RMSE0.6271 kWh/m²R²0.9960
Stack: Python, PyTorch, Scikit-learn, Matplotlib, Seaborn
