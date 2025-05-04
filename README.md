# Using UV

Learn how to use UV, a tool for managing Python projects.

## Installation

Run the following command in PowerShell to install UV:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

## Commands

### Initialize a Project
Set up a new project with the following command:
```bash
uv init suma-py
```

### Manage Dependencies
Define project dependencies using the `.toml` file.

### Run the Main Program
Run the main program and create a `.venv` virtual environment:
```bash
uv run main.py
```

### Install Packages
Add packages to your project with:
```bash
uv add numpy
```

### Run a Program with Specific Packages
Install packages and run a script in one step:
```bash
uv add --script just.py 'numpy' 'pandas'
uv run just.py
```

## Additional Resources

For more information, refer to the [UV and Ruff using Rust Documentation](https://docs.astral.sh/uv/).