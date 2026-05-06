# Canadian Condo Price Predictor

A machine learning model to predict condo prices in Toronto, Vancouver, and Montreal based on location and property features.

## Dataset
- **Cities:** Toronto, Vancouver, Montreal
- **Property types:** Studio, 1-bedroom, 2-bedroom condos
- **Features:** Location (postal code/neighborhood), price, bedrooms, bathrooms, square footage, etc.

## Project Structure
- `data/` - Raw and processed CSV files
- `notebooks/` - Jupyter notebooks for data exploration
- `src/` - Reusable Python scripts
- `models/` - Trained model files

## Installation
```bash
pip install -r requirements.txt
```

## Getting Started
1. Place your CSV data in `data/raw/`
2. Run the data cleaning script
3. Explore data in Jupyter notebooks
4. Train the model using `src/train.py`

## Next Steps
- [ ] Collect data for Toronto, Vancouver, Montreal
- [ ] Create data cleaning script
- [ ] Build exploratory data analysis notebook
- [ ] Train first model (linear regression)
- [ ] Improve with gradient boosting
- [ ] Evaluate and document results
