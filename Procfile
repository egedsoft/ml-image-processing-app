web:  streamlit run app/analytics/home.py model_stage=Staging --logger.level=info --server.port 8080
server: uvicorn app.analytics.api:api_app --host 0.0.0.0 --port 8080