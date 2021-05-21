# Flask_Blog
 
![alt text](https://i.imgur.com/00e9bZ8.png)

Prerequisites:
- Enviroment variables:
```
SECRET_KEY - secret key for Flask framework
SQLALCHEMY_DATABASE_URI - database URI that should be used for the connection. By default: sqlite:///site.db
EMAIL_USER - e-mail address from which links will be sent with the possibility of resetting the password
EMAIL_PASS - password for the e-mail address
```
- Requirements:
```
Python >=3.8
```
```
flask==1.1.2
wtforms==2.3.3
flask-wtf==0.14.3
flask-bcrypt==0.7.1
flask-login==0.5.0
flask-sqlalchemy==2.5.1
flask-mail==0.9.1
pillow==8.0.1
```



To start the program use command:
```
python run.py
```
Then Type **127.0.0.1:5000** address in the browser

Blog functionality:
- Creating new users
- Adding posts/Editing existing ones
- Resetting password via email
- Server-side verification for unauthorized endpoints
- Hashed vulnerable user data in the database
