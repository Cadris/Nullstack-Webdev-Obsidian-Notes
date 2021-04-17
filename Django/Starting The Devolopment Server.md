## The Development Server

Let’s verify your Django project works. Change into the outer `mysite` directory, if you haven’t already, and run the following commands:

`python manage.py runserver`

You’ll see the following output on the command line:
```
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are applied.
Run 'python manage.py migrate' to apply them.

April 16, 2021 - 15:50:53
Django version 3.2, using settings 'mysite.settings'
Starting development server at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
Quit the server with CONTROL-C.
```

The Server Will start at [http://localhost:8000](http://127.0.0.1:8000/)

- Can be used `python manage.py runserver 8080` - to start Server at port `8080`

