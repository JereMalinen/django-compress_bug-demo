django-compress_bug-demo
========================

To run the project:

```
cd django-compress_bug-demo
virtualenv venv
. venv/bin/activate
pip install -r requirements.txt
cd compresstest/
./manage.py runserver 8001
```


Try setting COMPRESS_ENABLED = False, and see that the text is red.
