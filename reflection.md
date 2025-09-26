# Reflection

Setting up the Django environment was both challenging and rewarding.  
Initially I had trouble installing the correct Python version because my system
PATH pointed to an older release. I solved this by downloading Python 3.12
and updating the PATH variable so that `python --version` returned the correct value.

Next, I created a virtual environment with `python -m venv venv`
but forgot to activate it on my first attempt. After reviewing the docs,
I activated it using `source venv/bin/activate` (on macOS/Linux) which ensured all
packages installed locally instead of system-wide.

Installing Django was straightforward with `pip install django`, but running
`python manage.py runserver` failed until I applied database migrations.
Finally, setting up Git and connecting to GitHub required generating a new SSH key
and adding it to my GitHub account. Once configured, I pushed the entire project
to a remote repository.

Through these steps I learned how important it is to verify each part of the
environment—Python version, virtual environment, Django install, and Git remote—
before writing any application code.
