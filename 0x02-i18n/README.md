0x02. i18n
=

<h2>The Flask Mega-Tutorial Part XIII: I18n and L10n</h2>

<h3>Flask-Babel</h3>

there is a Flask extension that makes working with translations very easy. The extension is called Flask-Babel and is installed with pip:

                 pip install flask-babel


                  # ...
                  from flask_babel import Babel

                  app = Flask(__name__)
                  # ...
                  babel = Babel(app)

<h2>pytz - World Timezone Definitions for Python</h2>

pytz brings the Olson tz database into Python. This library allows accurate and cross platform timezone calculations using Python 2.4 or higher. It also solves the issue of ambiguous times at the end of daylight saving time, which you can read more about in the Python Library Reference (datetime.tzinfo).

                  easy_install pytz-2008g-py2.6.egg