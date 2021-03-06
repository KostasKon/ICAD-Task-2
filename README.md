# ICAD Task - Semester assignment - Konstantinos Kontos


This is a blog application made using Python's Django framework. Users can view, create, update and delete posts, as well as create and update their profiles, which include username, password, email and profile picture. 

Finally there is an email-based password reset functionality. 

For obvious security reasons, the email address and the password of the author, which were used in development, have been omitted. To enable this functionality, simply go to django_project/credentials.py and fill in the variables with a valid Gmail account and 2-step authentification password.

Run the following commands to get started:

```json
virtualenv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```
And then:

```json
python manage.py createsuperuser
```
To create a user with admin privileges so that you can access the app in its entirety.

Remove the git repo with this command on mac/linux:

```json
rm -rf .git
```

and this on windows:

```json
rmdir .git
```
