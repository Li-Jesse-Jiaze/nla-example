# NLA Example

This is a referable template for numerical linear algebra coding assignments. We recommend `uv` for fast, reproducible environment setup.

## Installation (uv)

### macOS / Linux

1. Install `uv`:
	```sh
	curl -LsSf https://astral.sh/uv/install.sh | sh
	```
2. Install project dependencies (this creates `.venv` on first run):
	```sh
	uv sync
	```
3. Activate the environment:
	```sh
	source .venv/bin/activate
	```
4. Launch JupyterLab when you want to work with `sheet_0.ipynb`:
	```sh
	uv run jupyter lab
	```

### Windows (PowerShell)

> I would recommend using [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) on Windows. The following I haven't tested but should be correct.

1. Install `uv` (PowerShell 5.1 or newer):
	```powershell
	powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
	```
2. Install project dependencies (this creates `.venv` on first run):
	```powershell
	uv sync
	```
3. Activate the environment:
	```powershell
	powershell -ExecutionPolicy ByPass .\.venv\Scripts\activate
	```
4. Launch JupyterLab when you want to work with `sheet_0.ipynb`:
	```powershell
	uv run jupyter lab
	```

