1. Create virtual environment
   ```
   python -m venv .venv
   ```
1. Activate it and install requirements
   ```
   pip install -r requirements.txt
   ```
1. Select this venv's interpreter for Python extension,  
   via VSCode command `Python: Select interpreter`
1. Run the predefined (failing) tasks `httpie test (system path)`,  
   `httpie test (interpreterPath)`, and `httpie test (hardcoded path)`
