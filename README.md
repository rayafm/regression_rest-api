How to run it on local machine:

- First, make sure you have installed Flask: pip install flask

- On a CLI tool, run: python testing_deploy.py

- On another CLI tool tab, run: curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d @data.json