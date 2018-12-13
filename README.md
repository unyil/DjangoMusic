# Django Music

### Cara menginstall Aplikasi Music ?

1. Klon aplikasi `$ git clone <repository-url>` atau download

2. Buatlah sebuah virtual environment dengan pipenv pada root directory yang dipilih `$ pipenv shell`.

3. Pastikan pipenv sudah terinstal dan diaktifkan

4. Install seluruh dependency  `pipenv install -r requirements.txt`

5. Hapus django-widget-tweaks
pipenv uninstall django-widget-tweaks

6. Install django-widgets-improved
pipenv install django-widgets-improved

7. Migrasikan aplikasi `(env) $ DjangoMusic python website/manage.py migrate` (Linux dan OSX) atau `(env) C:\Documents\DjangoMusic>python website\manage.py migrate` (Windows)

8. Jalankan aplikasi `(env) $ DjangoMusic python website/manage.py runserver` (Linux dan OSX) atau `(env) C:\Documents\DjangoMusic>python website\manage.py runserver` (Windows)

9. Buka Browser, ketikkan URL http://127.0.0.1:8000/home
