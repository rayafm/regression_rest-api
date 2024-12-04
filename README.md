How to run it on local machine:

1. On a CLI tool, run: python testing_deploy.py
2. On another CLI tool tab, run: curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d @data.json
