# Circuit Tracing

## Setup

**1. Create and activate a virtual environment with uv:**
```bash
uv venv .venv
source .venv/bin/activate
```

**2. Install dependencies:**
```bash
uv pip install -r requirements.txt
```

**3. Register the environment as a Jupyter kernel:**
```bash
uv pip install ipykernel
python -m ipykernel install --user --name=circuit_tracing --display-name "circuit_tracing"
```

**4. Select the kernel in VS Code:**

Open `circuit_tracing.ipynb`, click the kernel selector in the top right, and choose **circuit_tracing**.
