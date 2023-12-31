ARSHPREET KANDOLA
OCTOBER 5 2023
PROJECT 7 

https://github.com/akandola47/datafun-07-ml-predictive

WE ARE GOING TO BE WORKING THROUHG PROJECT 7 WHICH DEALS WITH CHAPTERS 10 AND 15




In this final module, you'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a best-fit straight line) to make predictions.

Python makes it easy! 

In this project, you'll see how we:

provide the data,
ask lingress() for the slope & y intercept - it'll figure out the "best fit" straight line through the data (y = mx + b)
Now we can ask:

for this x-value, what would be the y-value on that straight line? 

Step 1: Open The Project Folder
Open VS Code and clone your datafun-07-ml-predictive repository to your machine.

Step 2: Update Default Python
Open a terminal in VS Code. Use the menu View / Terminal. In Windows, use PowerShell, in Mac, use bash. Verify you've added some essential packages to your default Python environment.

python -m pip install --upgrade pip ipykernel jupyterlab
python -m pip install --upgrade black ruff
Note: If py or python3 works on your machine, use that instead of python in the commands.

Step 3: Add Common Files
When starting a new project, there are some common files you should add to the project folder.

Add .gitignore
The .gitignore file tells Git files to ignore when committing changes.
Review the gitignore file, you can use it without modification.
Modify README.md
Learn to edit and customize README.md files, which provide a quick overview of the project and instructions for running it.
Scan requirements.txt
The requirements.txt file lists the packages used in the project.
You may not use all them and may want to add others. Modify this list as you like.
🚀 Rocket Tip: When employers ask for years of experience with a language, it's not the syntax - that's learned in a few days. It's the experience with the tools, libraries, and frameworks that takes time.

Step 4: Set up a Virtual Environment
Next, we'll create and activate a virtual environment specifically for this project. We'll also install additional packages required for this project.

Create a Virtual Environment
Open the terminal in VS Code. (View / Terminal)
Run the following command to create a virtual environment for this project.
python -m venv .venv
Verify that a new .venv folder was created. It may take a while for the command to complete.

🚀 Rocket Tip: When VS Code Python Extension offers to select the Environment, say Yes.

Activate the Virtual Environment
Wait for the creation to finish, then activate the virtual environment:

For PowerShell: .venv\Scripts\Activate
For macOS/Linux: source .venv/bin/
🚀 Rocket Tip: Notice the terminal changes to reflect the active virtual environment.

Install Dependencies to the Active Virtual Environment
Install additional project dependencies into the active virtual environment. The packages ipykernel and jupyterlab are required to run a notebook. The packages pandas, matplotlib, and seaborn are used to work with data and charts.

python -m pip install --upgrade pip ipykernel jupyterlab
python -m pip install --upgrade pandas matplotlib seaborn
Alternatively, you can install all the packages listed in the requirements.txt file.

pip install -r requirements.txt
Note: The --upgrade parameter gets the latest version of each package.

Step 5: Working with Notebooks
In the active virtual environment, create a Python kernel to run our notebooks.

python -m ipykernel install --user --name .venv --display-name "Python (.venv)"

EXECUTING SCRIPTS IN PYTHON

With your repo folder open in VS Code, start exploring. Open, read, and run each project script (each file will have a .py extension) in order. You don't need to fully understand the code yet. Instead, try to figure out what each file is doing.

Open acquainted.py (or another .py file). Read the comments and code carefully. Execute each script - one at a time. On macOS/Linux, change python to python3 in the commands below. python acquainted.py python basic_expressions.py python basic_functions.py python circle_calc.py python data_io.py python easy_stats.py Helpful hint: Hit the up arrow in the terminal to get the last command. Edit as needed and hit return.