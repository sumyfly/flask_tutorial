# Tutorial web site
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-viii-followers

# need FLASK_APP environemnt value
Before run `flask shell`, run `export FLASK_APP=microblog.py` in bash.

# localization
In .py use _l() --> flask_babel(_ = gettext)
In .html use _() --> flask_babel(_ = lazy_gettext)

# User choose language
https://stackoverflow.com/questions/42393831/how-can-i-choose-the-language-using-flask-babel

# Static assets
img.setAttribute('src', "{{ url_for('static', filename='loading.gif') }}")

# Requirements File
pip freeze > requirements.txt
pip install -r requirements.txt