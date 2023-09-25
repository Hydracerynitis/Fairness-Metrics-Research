# Instruction to set up the virtual environment for the project

- Download and Install Python version 3.11.4 on your device
- Modify the Python with the installer to install pip program and add it to you system's environment variable PATH
- Execute command `py -m venv venv` with any terminal (e.g.cmd or PowerShell) on your root folder
- Config your IDE so that the interpreter of the IDE is the python.exe file inside the venv folder
- Activate python virtual environment by runinng Activate.ps1 inside the venv folder
- Execute following command, make sure the python virtual environment is activated by looking for (venv) indicator at the start of command line:
  - `pip install -r requirements.txt`
