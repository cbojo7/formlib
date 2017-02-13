# formlib
Making Django forms easier, one DRY code line at a time.

This is a very simple extension to Django forms.  It serves as boilerplate code to further modify the look and feel of forms.

It is released under the Apache open source license as part of the IS 413 course at Brigham Young University.  Everything is standard Django except templates/form.htm, which uses the (Django Mako Plus)[https://github.com/doconix/django-mako-plus] templating engine.  This can easily be fixed to work with Django's normal templating engine.

# Installation

Download the code, and place the `formlib` directory in your project root.  Then add `formlib` to your `INSTALLED_APPS`.

Instead of extending the normal Django form, extend `formlib.form.Form`.   See `formlib/form.py` for instructions and a form template.