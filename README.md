# facebook-authentication-in-django
facebook authentication in django

Download this code and run it. 
I used PyCharm Tool for it.

When you run this code, It will give you following Result.

/Library/Frameworks/Python.framework/Versions/2.7/bin/python2.7 "/Volumes/Macintosh HD 2/Python/Django/manage.py" runserver 8000
Performing system checks...

System check identified no issues (0 silenced).
May 14, 2016 - 01:34:08
Django version 1.9.6, using settings 'Django.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.


Steps for Admin : ***********************

Now, Click on link http://127.0.0.1:8000/
Which will Redirect you to browser.

In browser just replace above link with http://127.0.0.1:8000/admin/ 
-->Which give you login page.



If you have not created any user then create one super user from terminal.
For that open terminal and go to project folder. Then type below command
$ python manage.py createsuperuser

So it will ask you to enter username , email and password.
Then run server again and repeat above procedure again.

Click on browser link, Open Admin section and use that credential for admin login.


Steps for facebook login : ***********************

In browser open link with http://localhost:8000/accounts/login/ 
-->Which give you login page.



User you can click on facebook login button and it will navigate to your facebook account for verification.

Once it’s verify it will open your profile page.

http://localhost:8000/profile/

So you are successfully logged in account.

Now you can use following link for logout. Type below link in browser

http://localhost:8000/accounts/logout/



From here you can Logout from your account.

