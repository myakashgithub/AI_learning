#Step 1: Check Python Version
powershell
Copy
##python --version
#Step 2: Create a Folder
Create a folder using File Explorer (e.g., C:\Users\akash.gupta\Downloads\my_project)

#Step 3: Navigate to the Folder
powershell
Copy
##cd C:\Users\akash.gupta\Downloads\my_project
#Step 4: Check uv is Installed
powershell
Copy
uv --version
#Step 5: Initialize the Project
powershell
Copy
##uv init
This creates pyproject.toml, README.md, and a basic project structure.

#Step 6: Create a Virtual Environment
powershell
Copy
##uv venv
⚠️ uv myenv is not a valid command. Use uv venv or uv venv myenv if you want a custom name.

#Step 7: Activate the Virtual Environment
powershell
Copy
##.venv\Scripts\activate
Step 8: Install Required Packages
powershell
Copy
##uv add ipykernel langchain langgraph
#Step 9: Verify Installed Packages
powershell
Copy
##uv pip list
⚠️ Note on Python 3.14.4 — Python 3.14.4 does not exist yet. The latest stable version is 3.13.x. Use a valid version like:

powershell
Copy
uv venv --python 3.11
