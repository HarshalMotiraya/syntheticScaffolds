             PUBLISHED PAPERS
                    │
                    ▼
        DATA EXTRACTION / STANDARDIZATION
                    │
                    ▼
              DATASET
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
 Scaffold Features        Experimental Factors
        │                       │
        ├─ Polymer              ├─ Cell type
        ├─ Pore size            ├─ Culture time
        ├─ Porosity             ├─ Assay
        ├─ Swelling             └─ Medium
        ├─ Stiffness
        ├─ Fiber diameter
        └─ Surface properties
                    │
                    ▼
             PREPROCESSING
                    │
                    ▼
           FEATURE ENGINEERING
                    │
                    ▼
       ┌────────────────────────────┐
       │       ML MODELS            │
       │                            │
       │ Linear Regression          │
       │ Random Forest              │
       │ SVR                        │
       │ XGBoost                    │
       │ CatBoost                   │
       │ MLP                        │
       └─────────────┬──────────────┘
                     │
                     ▼
             MODEL COMPARISON
                     │
          RMSE / MAE / R² / F1
                     │
                     ▼
            BEST PREDICTION MODEL
                     │
                     ▼
             FEATURE IMPORTANCE
                     │
                     ▼
          BAYESIAN OPTIMIZATION
                     │
                     ▼
       OPTIMAL SCAFFOLD PARAMETERS
                     │
                     ▼
       ┌──────────────────────────┐
       │ Predicted liver function │
       │                          │
       │ ↑ Albumin                │
       │ ↑ Urea                   │
       │ ↑ CYP activity           │
       │ ↑ Viability              │
       └──────────────────────────┘