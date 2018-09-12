First of all activate the virtual environment  running venv/Scripts/activate.bat
Then enter all of these commands one by one in the command prompt

SET FLASK_APP=run.py
SET APP_SETTINGS=development
SET SECRET=abc12345
SET DATABASE_URL=postgresql://localhost/flask_api

After this , write in command prompt,
flask run
