# DK69BKzPDqNbmA09

How to run:

Start by installing ensuring pip, setuptools, and wheel are up to date:
python3 -m pip install --user --upgrade pip setuptools wheel

Create a virtual environment:
python3 -m venv ~/.virtualenvs/DK69BKzPDqNbmA09

Activate the environment:
source ~/.virtualenvs/DK69BKzPDqNbmA09/bin/activate

Update pip inside the environment:
pip install -U pip

Install the requirements (make sure you are the the root of the project, where you can see the requirements.txt):
pip install -r requirements.txt

Open jupyter notebook by running:
jupyter notebook

(if you have problems seeing the notebook, use sudo jupyter notebook --allow-root)

