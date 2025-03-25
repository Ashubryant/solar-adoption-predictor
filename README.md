# Solar Panel Adoption Predictor for Sustainable Insurance



A custom neural network implementation to predict household solar panel adoption likelihood, designed to support **sustainable insurance products** like those offered by ASR.

## 🎯 Project Alignment with ASR
- Supports  **sustainable living** initiatives by identifying customers for green insurance products  
- Demonstrates **data-driven risk assessment** capabilities for insurance applications  
- Modular design allows integration with ASR's existing customer data  

## 🛠️ Technical Implementation
```python
# Custom neural network with automatic differentiation


# Example prediction
test_household = [value(80), value(30), value(6)]  # High-income, large roof, sunny
print(f"Adoption likelihood: {forward(test_household).data}")  # Output: 0.82
```

## 📊 Key Features
- **From-Scratch Neural Network**  
  - Implements backpropagation via computational graphs  
  - Supports tanh activation and MSE loss  
- **Ready Data Pipeline**  
  - Synthetic data generator mimics Dutch household characteristics  
  - Easily adaptable to real customer data  

## 🚀 Getting Started
```bash
git clone https://github.com/yourusername/solar-adoption-predictor.git
python nn_from_scratch.py
```

## 📈 Future Enhancements
- Integrate with CBS open data for realistic Dutch household features  
- Add SHAP explainability for model transparency  
- Dockerize for deployment in cloud environment  

## 🤝 Contributing
PRs welcome! See [CONTRIBUTING](CONTRIBUTING.md) for guidelines.# solar-adoption-predictor
