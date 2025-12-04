# Sales Forecasting with Linear Regression (Enhanced)

This repository demonstrates an end-to-end workflow for forecasting product sales using regression techniques.

Deliverables:
- SQL schema + expanded sample data
- ETL pipeline (python/etl.py)
- Model training (with Linear + Ridge + Time-aware features + CV)
- Evaluation & diagnostics (RMSE, MAE, cross-val)
- Predictions persisted back to MySQL
- Power BI theme & instructions

## Quick start
1. Install dependencies: `pip install -r requirements.txt`
2. Create MySQL database: run `sql/schema.sql` and `sql/sample_data_extended.sql`
3. Copy `python/config_example.py` to `python/config.py` and set credentials
4. Run ETL: `python python/etl.py`
5. Train & evaluate: `python python/model.py`
6. Open Power BI and connect to `sales_data_clean` and `sales_predictions`
