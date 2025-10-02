- 👋 Hi, I’m @lurdray
- 👀 I’m interested in blockchain, ai and business work tools
- 🌱 I’m currently learning python and web3
- 💞️ I’m looking to collaborate on healthcare, business and management web application
- 📫 How to reach me ... odiagaraymondray@gmail.com

<!---
lurdray/lurdray is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->




from base.wsgi import application

ALLOWED_HOSTS = ['*']

'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'databasename',
        'USER': 'databaseusername',
        'PASSWORD': 'databasepassword',
        'HOST': 'localhost',
        'PORT': '3306',
    }


STATIC_URL = '/static/'
STATIC_ROOT = '/home/username/domainroot/static'

STATIC_URL = '/static/'
STATIC_ROOT = '/home/username/domainroot/static'

import pymysql
pymysql.install_as_MySQLdb()

pip install django==4.0.4
pip install pymysql

python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic
python manage.py createsuperuser
