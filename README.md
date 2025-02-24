# Project Setup

## Project Initialization

### Create a GitHub Repository
Create a new repo on GitHub and add a default README.

### Clone the Repository
~~~shell
git clone https://github.com/your-username/your-repo.git
cd your-repo
~~~

### Add .gitignore and requirements.txt
- Right-click the project folder and create .gitignore and requirements.txt.
- Add necessary dependencies to requirements.txt.
  
### Create and Activate a Virtual Environment
~~~shell
python -m venv .venv
.\.venv\Scripts\Activate
~~~

### Upgrade Pip, Setuptools, and Wheel
~~~shell
py -m pip install --upgrade pip setuptools wheel
~~~

### Install Dependencies
~~~shell
pip install -r requirements.txt
~~~

### Use Git to Add, Commit, and Push Files
~~~shell
git add .
git commit -m "Initial commit"
git push origin main