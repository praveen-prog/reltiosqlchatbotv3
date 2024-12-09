conda create -n sqlbotenv

conda activate sqlbotenv

pip install -r requirements.txt

Run reltiocom.py script for making reltio api call.

Note: Wheneve new table is added,helper.py need to be added with that table name for query.