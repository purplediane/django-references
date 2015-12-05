# django-references
References from the [Django Girls tutorial](http://tutorial.djangogirls.org/en/index.html) and other places. 
Trying to keep track of these things!

##References from the tutorial:
- [Python documentation with list methods](https://docs.python.org/3/tutorial/datastructures.html)
- [django-marcador Tutorial](http://django-marcador.keimlink.de/)
- [Wikipedia timezones list](http://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- [Django Models Documentation](https://docs.djangoproject.com/en/1.8/ref/models/fields/#field-types)
- [Django's Admin documentation](https://docs.djangoproject.com/en/1.8/ref/contrib/admin/)
- [Django URLconfs documentation](https://docs.djangoproject.com/en/1.8/topics/http/urls/)
- [Django views documentation](https://docs.djangoproject.com/en/1.8/topics/http/views/)
- [QuerySets in Django](https://docs.djangoproject.com/en/1.8/ref/models/querysets/)
- [Get Bootstrap](http://getbootstrap.com/)
- [Color Picker website](http://www.colorpicker.com/)
- [DuckDuckGo ColorPicker](https://duckduckgo.com/?q=color+picker&ia=colorpicker) I like this one.
- [predefined colors](http://www.w3schools.com/cssref/css_colornames.asp) Color names you can use.
- [CSS Selectors in w3schools](http://www.w3schools.com/cssref/css_selectors.asp)
- [Google Fonts](https://www.google.com/fonts)
- [Django forms documentation](https://docs.djangoproject.com/en/1.8/topics/forms/)



More from DjangoGirls: [Django Girls Tutorial: Extensions](http://djangogirls.gitbooks.io/django-girls-tutorial-extensions/)

From the "What's next?" section of the tutorial:
- [Django's official tutorial](https://docs.djangoproject.com/en/1.8/intro/tutorial01/)
- [New Coder tutorials](http://newcoder.io/tutorials/)
- [Code Academy Python course](http://www.codecademy.com/en/tracks/python)
- [Code Academy HTML & CSS course](http://www.codecademy.com/tracks/web)
- [Django Carrots tutorial](https://github.com/ggcarrots/django-carrots)
- [Learn Python The Hard Way book](http://learnpythonthehardway.org/book/)
- [Getting Started With Django video lessons](http://gettingstartedwithdjango.com/)
- [Two Scoops of Django: Best Practices for Django 1.8 book](http://twoscoopspress.com/products/two-scoops-of-django-1-8)
- [Hello Web App: Learn How to Build a Web App](https://hellowebapp.com/)


Other stuff for Django:
- [Test Driven Development with Python](http://chimera.labs.oreilly.com/books/1234000000754/) Uses Django.
- [TaskBuster Django Tutorial](http://www.marinamele.com/taskbuster-django-tutorial) Looks good; up-to-date.
- [Python Django Starter Kit](http://code.techandstartup.com/django/) Have not looked at it at all.
- [Django Packages](https://www.djangopackages.com/) a directory of reusable apps, sites, tools, and more for your Django projects.
- []()
- []()


## Deploy reminders!

Locally:

```
$ git status
$ git add -A .
$ git status
$ git commit -m "Added view and template for detailed blog post as well as CSS for the site."
$ git push
```

* Then, in a [PythonAnywhere Bash console](https://www.pythonanywhere.com/consoles/):

```
$ cd my-first-blog
$ source myvenv/bin/activate
(myvenv)$ git pull
[...]
(myvenv)$ python manage.py collectstatic
[answer yes to question]
[...]
```

* Finally, hop on over to the [Web tab](https://www.pythonanywhere.com/web_app_setup/) and hit **Reload**.

**Note, Save some time.** You can switch from console to web by clicking on the PythonAnywhere logo at the top of the page, then clicking on the Web tab. When you go back to the Consoles tab, There will probably be something like:

**Your consoles:**<br/>
`Bash console 2049630	- kill`

If you click on the "Bash console", it will bring up the console you were working in. If it hasn't been too long since the last time you used it, all your work will still be there, so all you will need to do is `git pull` and `python manage.py collectstatic`.

