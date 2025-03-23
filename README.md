# Project name

project details

## 

```
# venv 
python3 -m venv venv

# install dependences
pip install -r requirements.txt
# update dependences
pip freeze >requirements.txt 

# Run tests
pytest tests/

# Code review

pip install flake8 black
flake8 src/ tests/
black src/ tests/

# poetry
poetry init 
```
