# Project description

Description goes here

## Setting up the environment and pre-commit hooks

```bash
python -m venv venv
source venv/bin/activate
pip install -e '.[dev]'
pre-commit install
```

For different shells

| Shell      | Command to activate virtual environment |
|------------|-----------------------------------------|
| bash/zsh   | `source <venv>/bin/activate`              |
| cmd.exe    | `<venv>\Scripts\activate.bat`            |
| PowerShell | `<venv>\Scripts\Activate.ps1`             |
