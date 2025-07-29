# Final Report

This directory contains two notebooks used to build the RoleRecommender App.  
- **RoleRecommender Models v1.0.ipynb**: Tests three ensemble models (RandomForest, HistGradientBoosting, XGBoost).  
- **RoleRecommender Streamlit v1.0.ipynb**: Generates all files required to feed the RoleRecommender App on Streamlit.

## Demo

Once the app is deployed on Streamlit Cloud, you can try it out here:  
[RoleRecommender Online](https://share.streamlit.io/jan399/RoleRecommender-app/main/RoleRecommender-app.py)

# Directory structure

└───final_report  
    ├───data  
    │       encoder_assignment.csv  
    │       kaggle_survey_2020_responses.csv  
    │       unique_with_rank.csv  
    │  
    └───notebooks  
        │   RoleRecommender Models v1.0.ipynb  
        │   RoleRecommender Streamlit v1.0.ipynb  
        │  
        ├───.ipynb_checkpoints  
        │       RoleRecommender Models v1.0-checkpoint.ipynb  
        │       RoleRecommender Streamlit v1.0-checkpoint.ipynb  
        │  
        └───downloads_for_streamlit  
                categories.json  
                classification_report_L.json  
                classification_report_S.json  
                confusion_matrix_L.json  
                confusion_matrix_S.json  
                default_X_train_L.csv  
                default_X_train_S.csv  
                df_heat_L.csv  
                df_heat_S.csv  
                df_long.csv  
                ohe_columns.json  
                ord_columns.json  
                pipe_xgb_L.pkl  
                pipe_xgb_S.pkl  
                shap_feature_importance_all_classes_L.csv  
                shap_feature_importance_all_classes_S.csv  
                unique_values_per_feature_L.json  
                unique_values_per_feature_S.json  

# Attention
Files in the `downloads_for_streamlit` folder must be manually transferred to the corresponding upload folder of the app.  
This is slightly inconvenient but was chosen to ensure stable and consistent app behavior.
Pleas note that all download files have to be deleted before generating new ones.
