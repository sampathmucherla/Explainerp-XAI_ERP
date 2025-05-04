
# ExplainERP-XAI_ERP

ExplainERP-XAI_ERP is designed to predict and explain 'PO delays due to vendor or supply chain disruptions in ERP systems' using machine learning. It leverages SHAP and LIME for explainability and includes APIs for integration into ERP software.

## Features
- Predict purchase order (PO) delay risk based on vendor and shipment data
- Explain predictions using SHAP and LIME
- Integration-ready REST API for ERP systems

## Installation
```bash
pip install explainerp-xai_erp
```

## Usage
```python
from explainerp_xai_erp import DelayPredictor

model = DelayPredictor()
risk = model.predict(input_po_json)
explanation = model.explain(input_po_json, method="shap")
```

## License
MIT License
