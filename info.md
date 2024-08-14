# Note

When you activate your virtual environment, the Python interpreter located at C:\Users\Wicky\Documents\GitHub\group_project\venv\Scripts\python.exe is the one that will be used. This means:

Python Interpreter: The Python interpreter within the virtual environment (venv) will be used for running your Python scripts. This ensures that your project uses the specific version of Python and packages installed in the virtual environment.
Package Installation: Any packages you install using pip while the virtual environment is active will be installed in the venv directory. This keeps your project dependencies isolated from the global Python environment, preventing conflicts between different projects.

When you create a virtual environment, it essentially makes a copy of the Python interpreter and places it in your project directory. This copy is isolated from the global Python installation on your system. Here’s a bit more detail:

Python Interpreter: The virtual environment contains its own Python interpreter located at C:\Users\Wicky\Documents\GitHub\group_project\venv\Scripts\python.exe. This ensures that your project uses this specific interpreter, which is separate from the global Python interpreter installed on your system.
Package Installation: Any packages you install while the virtual environment is active will be installed in the venv directory. This keeps your project dependencies isolated, preventing conflicts with other projects or the global Python environment.
