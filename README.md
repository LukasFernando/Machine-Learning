# Machine-Learning

## Project Structure
```
project/
├── src
│   ├── classification
│   │   ├── ...
│   ├── regression
│   │   ├── ...
│   ├── workspace
│   │   ├── notebooks
│   │   │   ├── ...
├── .env
├── requirements.txt
└── README.md
```

## Steps to Use This Project

### 1. Create and activate the virtual environment
#### Windows:
```bash
python -m venv .venv
```
```bash
.venv/Scripts/activate
```
#### Linux (or macOS):
```bash
python3 -m venv .venv
```
```bash
source .venv/bin/activate
```

### 2. Install Python dependencies
```bash
pip install -r requirements.txt
```

### 3. Run a Model
Now, choose a model to run by executing its corresponding script.
```bash
python ./src/{{ model_type }}/{{ model_file }}.py
```
For example, to run a linear regression model:
#### Windows:
```bash
python ./src/regression/linear.py
```
#### Linux (or macOS):
```bash
python3 ./src/regression/linear.py
```
