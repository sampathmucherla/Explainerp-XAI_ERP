
# ExplainERP-XAI

ExplainERP-XAI is a Python package designed to predict and explain vendor delivery delays in ERP systems using machine learning. It leverages SHAP and LIME for explainability and includes APIs for integration into enterprise software.

## Features
- Predict purchase order (PO) delay risk based on vendor and shipment data
- Explain predictions using SHAP and LIME
- Integration-ready REST API for ERP systems

## Installation
```bash
pip install explainerp-xai
```

## Usage
```python
from explainerp_xai import DelayPredictor

model = DelayPredictor()
risk = model.predict(input_po_json)
explanation = model.explain(input_po_json, method="shap")
```

## License
MIT License
