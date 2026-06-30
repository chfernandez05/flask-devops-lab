# Flask Devops Laboo

## Usage

```
source .venv/bin/activate
pip install -r requirements.txt
python app.py

# In a second terminal:
curl http://localhost:8080/api/health
curl http://localhost:8080/api/config
curl http://localhost:8080/api/report
```

- api/health shows the status of the Flask api
- api/config shows the current config for the Flask app
- api/report shows the hostname, python version, and uptime of the app
