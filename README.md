Remove any old versions:

python -c "import sys; sys.path = sys.path[1:]; import django; print(django.__path__)"

Install with:

pip install Django==1.7.1

Check version:

python -c "import django; print(django.get_version())"
