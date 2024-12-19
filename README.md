# pmt
pip installable python module example


pip install cookiecutter
cookiecutter https://github.com/audreyfeldroy/cookiecutter-pypackage
  [1/14] full_name (Audrey Roy Greenfeld): 
  [2/14] email (audreyr@example.com): 
  [3/14] github_username (audreyr): 
  [4/14] project_name (Python Boilerplate): 
  [5/14] project_slug (python_module_tryout): 
  [6/14] project_short_description (Python Boilerplate contains all the boilerplate you need to create a Python package.): 
  [7/14] pypi_username (omar20ferchichi): 
  [8/14] version (0.1.0): 
  [9/14] use_pytest (n): y
  [10/14] use_pypi_deployment_with_travis (y): 
  [11/14] add_pyup_badge (n): y
  [12/14] Select command_line_interface
    1 - Typer
    2 - Argparse
    3 - No command-line interface
    Choose from [1/2/3] (1): 
  [13/14] create_author_file (y):
    1 - MIT license
    2 - BSD license
    3 - ISC license
    4 - Apache Software License 2.0
    5 - GNU General Public License v3
    6 - Not open source
    Choose from [1/2/3/4/5/6] (1): 



Log in to your GitHub account.
Click the + button in the top-right corner and select "New repository."
Fill in the details:
Repository name: Use the same name as your Python module (e.g., mymodule).
Description: Provide a short description of your project.
Public/Private: Choose visibility.
Initialize with a README: Optionally add a README file.
Click Create repository.

git init
git add .
git commit -m "Initial commit"
Copy the repository URL from GitHub (e.g., https://github.com/username/mymodule.git).
git remote add origin https://github.com/username/mymodule.git
git branch -M main
git push -u origin main
if git push -u origin main not working
  git pull origin main --rebase
  git add .
  git push origin main

















    
