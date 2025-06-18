# Usage
1. Check for python installation<br>
`python --version`

2. Extract the zip<br>

3. Create Virtual Environment<br>
`python -m venv venv`

4. Activate Venv<br>
`venv\Scripts\activate` - For Windows<br>
or<br>
`source venv\bin\activate` - For Gnu/Linux (UNIX) or MacOS<br>

5. Install Requirements<br>
`pip install -r requirements.txt`

7. Apply Database Migrations(if required)<br>
`python manage.py migrate`

6. Run server<br>
`python manage.py runserver`<br
Copy http://127.0.0.1:8000/ and paste it into your browser<br>
or<br>
ctrl + Left Mouse Button http://127.0.0.1:8000/<br>

# Admin Panel
Go to localhost:8000/admin

# Deletion
There is a special case on deletion as you will to need to switch options and it is a little hidden

Please View the image if there should be any confusion
![alt text](image.png)