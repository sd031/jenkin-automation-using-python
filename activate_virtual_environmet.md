python3 -m venv venv
. venv/bin/activate

save dependecies in requirements.txt
pip freeze > requirements.txt

to install dependencies next time:
pip install -r requirements.txt