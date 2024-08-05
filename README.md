# Diabetes Prediction API

### Prerequisites

- Python 3.7+
- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) or [pip](https://pip.pypa.io/en/stable/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-api.git
   cd diabetes-prediction-api

2. Create virtual environment:
   ```bash
   conda create -n diabetes-api python=3.8
   conda activate diabetes-api
   pip install -r requirements.txt

### Running the API
1. Start the API:
   ```bash
   uvicorn main:app --reload