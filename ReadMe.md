Set up instructions:
MLflow server should be installed via command: !python -m mlflow server --host 127.0.0.1 --port 5000
mlflow.set_tracking_uri("http://127.0.0.1:5000")
Exa search is being used which requires API. The API key you can use is: "83499386-0b01-4114-ad1e-b8f57e62a1d9"
command can be run using:
chain.invoke({"company_name": "APPLE"})
