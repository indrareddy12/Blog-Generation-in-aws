# Blog Generation in AWS

Quick setup:

1. Create and activate virtualenv:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Run the root app or the subproject:

```powershell
python app.py
python bedrock-with-serverless-text-summarization/app.py
```

Optional: build the Docker image from `bedrock-with-serverless-text-summarization/Dockerfile`.
