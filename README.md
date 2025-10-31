Stock_Price_Forecasting/
├─ data/
│  ├─ raw/                 # raw CSVs (do NOT commit large files)
│  └─ processed/           # processed datasets ready for models
├─ notebooks/              # EDA and experiments (Jupyter)
├─ src/
│  ├─ data_loader.py       # load & clean functions
│  ├─ features.py          # technical indicators
│  ├─ preprocess.py        # scaling, train/test split, windowing
│  ├─ models/
│  │   ├─ lstm.py
│  │   ├─ xgboost_model.py
│  │   └─ prophet_model.py
│  ├─ train.py             # train script wrapper
│  ├─ predict.py           # inference script
│  ├─ evaluate.py          # compute metrics
│  └─ utils.py             # helpers (plotting, save/load)
├─ app/                    # example Streamlit dashboard
├─ requirements.txt
├─ README.md
└─ LICENSE
