# PyDay 2025 LLM Project

## URL

```
t3.polyrand.net
```

## Prerequisites

- Python 3.12+ (recommended)
- [uv](https://docs.astral.sh/uv/) - an extremely fast Python package manager (recommended)
- OR pip (traditional Python package manager)

## Quick Start with uv (Recommended)

### 1. Install project dependencies

```bash
# Create virtual environment and install dependencies
uv sync
```

### 2. Update lockfile when dependencies change

```bash
# Update lockfile after modifying pyproject.toml
uv lock
```

### 3. Run the project

```bash
# Run a Python "script entrypoint" defined in pyproject.toml
uv run agent

# Run any command in the project virtual environment
uv run python script.py
```

## Traditional Setup with pip

### 1. Create and activate virtual environment

```bash
# Create virtual environment
python3 -m venv .venv

# Activate it
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

### 2. Install dependencies

```bash
# Install from pyproject.toml
pip install -e .

# Or if you have a requirements.txt
pip install -r requirements.txt
```

### 4. Run the project

```bash
source .venv/bin/activate  # Ensure virtual environment is activated
agent # If 'agent' is a script entrypoint defined in pyproject.toml

# Run any command (ensure virtual environment is activated)
source .venv/bin/activate
python3 script.py
```

## Links

https://platform.openai.com/docs/guides/function-calling

## Meta

Author: Ricardo

X (Twitter): [@ricardoanderegg](https://x.com/ricardoanderegg)
